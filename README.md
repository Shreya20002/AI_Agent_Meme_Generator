# AI Agent Meme Generator

The AI Meme Generator Agent is a powerful browser automation tool that creates memes using AI agents. This application combines multi-LLM capabilities with automated browser interactions to generate memes based on text prompts through direct website manipulation.

## Features

### Multi-LLM Support
- **Claude 3.5 Sonnet** (Anthropic)
- **GPT-4o** (OpenAI)
- **Deepseek v3** (Deepseek)
- Automatic model switching with API key validation

### Browser Automation
- Direct interaction with [imgflip.com](https://imgflip.com/) meme templates
- Automated search for relevant meme formats
- Dynamic text insertion for top/bottom captions
- Image link extraction from generated memes

### Smart Generation Workflow
- Action verb extraction from prompts
- Metaphorical template matching
- Multi-step quality validation
- Automatic retry mechanism for failed generations

### User-Friendly Interface
- Model configuration sidebar
- API key management
- Direct meme preview with clickable links
- Responsive error handling

## Requirements

### API Keys
You'll need the following API keys:
- [Anthropic API Key](https://console.anthropic.com/) (for Claude)
- [Deepseek API Key](https://platform.deepseek.com/) 
- [OpenAI API Key](https://platform.openai.com/) (for GPT-4o)

### Workflow Diagram

graph TD
    A[User Input] --> B[Action Extraction]
    B --> C[Template Matching]
    C --> D[Caption Generation]
    D --> E[Browser Automation]
    E --> F[Quality Validation]
    F --> G[Output Result]

### How to Run

1. Clone the repository
   git clone https://github.com/Shreya20002/AI_Agent_Meme_Generator.git
   
2. Install the dependencies
   pip install -r requirements.txt

3. Run the streamlit app:
   streamlit run ai_meme_generator.py
