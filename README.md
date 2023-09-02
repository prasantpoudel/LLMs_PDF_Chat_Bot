# Chat With PDF
![Alt text](https://file%252B.vscode-resource.vscode-cdn.net/var/folders/ny/9v084qqs5bv3c8gmyggl1ypc0000gn/T/TemporaryItems/NSIRD_screencaptureui_kP0X0P/Screenshot%25202023-09-02%2520at%25201.19.54%2520PM.png?version%253D1693640101474)
The goal of the project is to ask any content present in the PDF. We can upload multiple Pdf and ask anything related to the pdf.

Step To Run Locally...

Step1> Clone this repo
        ```bash
        https://github.com/prasantpoudel/LLMs_PDF_Chat_Bot.git
        ```

Step2 > Download all the requrements files
        ```bash
        pip install -r requirements.txt
        ```

Step3> Change the .env.example file to .env file.

Step4> Add all the api of the OpenAI if you are using OpenAI Embedding.
        Also you can use the Hugging face Api.
        (OpenAi Embdedding are costly and can give the timeouterror if you are using free api)
        (HuggingFace api are free but slower to process the text)

Step5> Run the main file
        ```bash
        Streamlit run main.py
        ```