# Langchain End to End (User txt to MQL)

This is full stack application with backend and frontend integration for User text to MQL.


## BackEnd
API link: http://127.0.0.2:8000

filegpt.json: It contain the input data in structured JSON format.

langchain_final.py: It contain all relevant function with langchain(OpenAI and huggingface).

main.py: It contain creation of FastAPI (Frontend API) with endpoint “langchain”.

requirements.txt:  It contain all the dependences for this project.

Data_update.csv: This file created from the preprocessing of input document data.

path_df.csv: This file is contain all path of the Data tree.

## FrontEnd
API link: http://127.0.0.1:5173/

client(folder) -> script.js : This .js file contain the front code 



## How to Run
Step1: 
Run man.py it show like below:
    Uvicorn running on http://127.0.0.2:8000 (Press CTRL+C to quit)
Now Backend FastAPI run successfully.
Step2:
Enter following cmd in the terminal:
    cd client
    npm run dev
if it show like below:
    Local:   http://127.0.0.1:5173/
Then FrontEnd run successfully. 
Step3:
Now open :   http://127.0.0.1:5173/ in browser .
 
Now you successfully  Langchain End to End Project !!
Ask your query then get MQL response.




