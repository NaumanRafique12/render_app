---
title: LlamaIndex Cloud Chat
emoji: 🦙
colorFrom: blue
colorTo: green
sdk: gradio
sdk_version: 4.19.0
app_file: app.py
pinned: false
---

# LlamaIndex Cloud Chat Interface

This is a Gradio application that allows users to chat with documents stored in LlamaIndex Cloud. The application is deployed on Hugging Face Spaces.

## Setup Instructions

### Prerequisites
1. A Hugging Face account
2. OpenAI API key
3. LlamaIndex Cloud API key
4. LlamaIndex Cloud Index ID (for your existing index)

### Deployment Steps

1. Create a new Space on Hugging Face
2. Add your API keys and index ID as secrets in the Hugging Face Space settings:
   - `OPENAI_API_KEY` - Your OpenAI API key
   - `LLAMA_CLOUD_API_KEY` - Your LlamaIndex Cloud API key
   - `LLAMA_CLOUD_INDEX_ID` - Your LlamaIndex Cloud Index ID

3. Upload these files to the Space:
   - `app.py`
   - `requirements.txt`
   - `README.md`
   - `.env.example` (for reference only)

### LlamaIndex Cloud Setup

This application assumes you have already:
1. Created an account on LlamaIndex Cloud
2. Created and uploaded your documents to an index
3. Obtained your index ID from the LlamaIndex Cloud dashboard

If you haven't completed these steps, please:
1. Sign up for LlamaIndex Cloud
2. Create a new index and upload your documents
3. Get your index ID from the dashboard
4. Add this index ID to your Hugging Face Space secrets

### Customization

You can customize the application by:
- Changing the LLM model in `app.py` (currently set to "gpt-3.5-turbo")
- Modifying the agent behavior or tools
- Adjusting the Gradio interface styling
- Adding more example questions

## Troubleshooting

If you encounter issues:
1. Check that your API keys and index ID are correctly set in Hugging Face Secrets
2. Verify that your LlamaIndex Cloud index exists and contains documents
3. Check Space logs for any error messages
4. Make sure your requirements.txt includes all necessary dependencies

## License

This project is open source and available under the MIT License.
#   r e n d e r _ d e p l o y _ i n d e x  
 #   r e n d e r _ a p p  
 #   r e n d e r _ a p p  
 #   l l a m a - g r a d i o - a p p  
 #   l l a m a - g r a d i o - a p p  
 