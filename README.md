# Medical-chatbot
<<<<<<< HEAD
# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & Vertex AI project credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
project_id = "xxxxxxxxxxx"
region = "xxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Vertex AI
- Pinecone

### Result of the chatbot
<img width="732" height="577" alt="image" src="https://github.com/user-attachments/assets/8331a7a2-a5b7-4874-ae4b-8af9f84ad5f8" />



