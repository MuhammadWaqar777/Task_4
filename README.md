General Health Query Chatbot

This is a simple **General Health Query Chatbot** built using the **TinyLLaMA-1.1B-Chat** model from Hugging Face.  
It runs in **Google Colab** (or locally) and answers safe, everyday health questions.  
Disclaimer: This bot is **not a doctor** and provides only general information.
##Features
- ✅ Runs **fully in Google Colab** (no installation on your PC needed)
- ✅ Uses **public Hugging Face model** (no login or token required)
- ✅ **Safety filter** to block dangerous medical queries
- ✅ Prompt-engineered for **clear and friendly** responses
- ✅ Can be extended into a **web interface** using Gradio
# How to Run in Google Colab
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Copy the chatbot code from this repository into a new cell.
3. Run the first cell to install dependencies:
   ```bash
   !pip install transformers torch accelerate
Run the chatbot cell.

Type a safe health question (example: "What are some healthy breakfast ideas?").

Type "exit" to quit.
💡 Example Questions
You can ask:

"What are signs of dehydration?"

"Give me tips for reducing stress."

"How much exercise should an adult get weekly?"

"What are benefits of eating fruits daily?"

