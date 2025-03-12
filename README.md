# PDF READ AI CHAT

This application uses Llama2-Chat Large Language Model with Chroma Vector Database to provide RAG. This allows the LLM to get context from the PDF document and answer the queries instead of having to be directly fine tuned (which is extremely compute expensive).

[Disclaimer]: Due to prevent unauthorized disclosure, no code is available for now, but I have provided a demo video run.

## Dependencies/Libraries used

Please check the following libraries as well as other potential libraries that are utilized in the app but not installed in the local environment. Ensure all of them are installed prior to running the application.

- streamlit
- PyPDF2 (PdfReader)
- sentence-transformers
- tiktoken
- chromadb

They can be installed via pip:
```bash
pip install streamlit
```
In addition the replicate token should be saved in .env file as:
```
REPLICATE_API_TOKEN = "[token]"
```
The token can be found [here](https://replicate.com/docs/guides/push-a-model).

## Usage

After libraries are checked, run the app via streamlit:
```bash
streamlit run app.py
```
## Video:
https://github.com/user-attachments/assets/77ead3aa-fe97-4d1c-917d-4b7b2df85ee9
