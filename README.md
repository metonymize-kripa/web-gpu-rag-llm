# In-Browser RAG + LLM with WebGPU Acceleration
This project demonstrates a simple in-browser application that combines Retrieval Augmented Generation (RAG) with a large language model (LLM) powered by WebGPU for accelerated inference.

## Features:

- WebGPU Acceleration: Leverages the power of WebGPU for faster LLM inference, enabling smoother and more responsive interactions.
- RAG Integration: Allows users to upload a .jsonl file containing a dataset of JSON objects. The application randomly selects and displays a few-shot example from the file.
- LLM Interaction: Utilizes the @mlc-ai/web-llm library to load and interact with a pre-trained LLM (currently Llama-3-8B-Instruct-q4f32_1-MLC).
- Prompt Submission: Users can input their prompts and receive responses from the LLM.
- Text Summarization: Includes a button to summarize the input text using the @xenova/transformers library.
Getting Started:

## Clone the repository:

git clone https://github.com/your-username/in-browser-rag-llm.git
Open index.html in a modern web browser: Ensure your browser supports WebGPU. Chrome and Firefox are recommended.

## Interact with the application:

Upload a .jsonl file containing your dataset.
Enter your prompts in the text area.
Submit prompts to receive responses from the LLM.
Use the "Summarize" button to generate a summary of the input text.

## Technical Details

- LLM: The application currently uses the Llama-3-8B-Instruct-q4f32_1-MLC model from MLC AI. You can explore other models supported by @mlc-ai/web-llm.
- RAG: The RAG functionality is implemented using a simple random selection from the uploaded .jsonl file. You can customize this to implement more sophisticated retrieval strategies.
- WebGPU: The @mlc-ai/web-llm library utilizes WebGPU for accelerated inference, significantly improving performance compared to traditional CPU-based execution.

## Future Improvements:

- Advanced RAG: Implement more sophisticated retrieval methods, such as embedding-based search.
- Model Selection: Allow users to choose from a wider range of LLMs supported by @mlc-ai/web-llm.
- User Interface: Enhance the user interface for a more intuitive and engaging experience.

Note:
This project is a starting point for exploring in-browser RAG and LLM applications with WebGPU acceleration. Feel free to modify and extend it to suit your specific needs.