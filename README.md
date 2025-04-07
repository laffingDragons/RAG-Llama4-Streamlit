
## RAG with Llama 4 and Cerebras 🚀🤖

Welcome to the Retrieval-Augmented Generation (RAG) app powered by Llama 4, Cerebras, and LlamaIndex! This Streamlit app lets you upload a PDF, index it, and chat with an AI that answers questions based on your document. Let’s get started! 📄💬

What Does This App Do?  
- **Upload PDFs**: Drop your .pdf files and let the app index them. 📤  
- **Chat with AI**: Ask questions, and get crisp answers based on your document. 🤖💡  
- **Smart Tech**: Uses Cerebras’ Llama 4 model and LlamaIndex for retrieval and generation. 🧠🔍  
- **Pretty UI**: Built with Streamlit for a smooth, interactive experience. 🎨✨

How to Set It Up 🔧  
**Prerequisites**  
- Python 3.8+ installed 🐍  
- A Cerebras API Key (see below for how to get one!) 🗝️  
- Images in an assets folder:  
  - cerebras.png  
  - llamaindex.png  

**Step-by-Step Setup**  
1. **Clone the Repo**  
```bash
git clone <your-repo-url>
cd <your-repo-name>
```  

2. **Install Dependencies**  
Create a `requirements.txt` with:  
```plaintext
streamlit  
llama-index  
llama-index-llms-cerebras  
llama-index-embeddings-fastembed  
python-dotenv  
ipython  
```  
Then run:  
```bash
pip install -r requirements.txt
```  

3. **Set Your API Key**  
**Option 1**: Add it to a `.env` file:  
```plaintext
CEREBRAS_API_KEY=your-api-key-here
```  
**Option 2**: Enter it in the app’s sidebar when you run it.  

4. **Run the App**  
```bash
streamlit run app.py
```  
Open your browser at `http://localhost:8501` and voilà! 🌐

How to Get a Cerebras API Key 🗝️  
To use this app, you’ll need a Cerebras API key. Here’s how to get one:  
1. **Visit Cerebras**: Go to cerebras.ai.  
2. **Sign Up**: Click “Sign Up” or “Get Started” (look for a registration button).  
3. **Fill in your details** to create an account.  
4. **Access the API Section**: Once logged in, navigate to the developer dashboard or API section (usually under your profile or a “Developers” tab).  
5. **Generate Your Key**: Look for an option like “Create API Key” or “Generate Key.”  
6. **Copy the key** provided—it’ll look like a long string of letters and numbers.  
7. **Use It**: Paste it into the `.env` file or the app’s sidebar when prompted.  

**Note**: If you don’t see an API option, check Cerebras’ documentation or contact their support—APIs might be in beta or require approval as of April 08, 2025! 🔑

How to Use It 🛠️  
1. **Enter API Key**: In the sidebar, paste your Cerebras API key (or set it in `.env` beforehand).  
2. **Upload a PDF**: Use the file uploader in the sidebar to add a .pdf file.  
3. **Wait for Indexing**: The app will process your PDF and say “Ready to Chat!” when done.  
4. **Ask Away!**: Type a question in the chat box (e.g., “What’s this PDF about?”).  
5. **Watch the AI respond** with answers from your document! 🎤🤖

Troubleshooting ⚠️  
- **“Enter your Cerebras API Key” Error?** Double-check your `.env` file or sidebar input.  
- **PDF Not Indexing?** Ensure the PDF isn’t corrupted or too complex (e.g., scanned images might not work).  
- **No Response?** Verify your Cerebras API key is valid and the model name is correct.  
- **Still Stuck?** Drop a message in the repo’s Issues tab, and I’ll help you out! 💬

Features 🌟  
- **Streaming Answers**: Watch the AI type out responses in real-time! ⏱️  
- **Clear Chat**: Hit the “Clear ↺” button to start fresh.  
- **PDF Preview**: See your uploaded PDF in the sidebar. 👀

Tech Stack 🛠️  
- **Frontend**: Streamlit 🌐  
- **LLM**: Cerebras (Llama-4-Maverick-17B-128E-Instruct-FP8) 🧠  
- **RAG**: LlamaIndex 🔎  
- **Embeddings**: FastEmbed (BAAI/bge-large-en-v1.5) 🧩

Contributing 🙌  
Got ideas? Found a bug? Feel free to:  
- Fork the repo  
- Submit a pull request  
- Open an issue  

**Last Updated**  
April 08, 2025 📅  
Enjoy chatting with your documents! Happy coding! 👨‍💻👩‍💻
