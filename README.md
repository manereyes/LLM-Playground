
# LLM Playground / Sandbox
<p align="center">
  <img src="https://github.com/user-attachments/assets/92d0c438-6f83-4d51-96ef-617d2ca671fa" width="700" height="400">
</p>
A simple project to learn the basics of LLM parameters, Prompt Engineering and LLM manipulation. The objetive of this project is to give developers a local playground to manipulate, play and test the different capabilities of their local LLMs.

## Frameworks.
- **Made** with [Python 3](https://www.python.org/) 🐍.
- **Built** with [Langchain](https://www.langchain.com/) 🦜🔗.
- **Used** [Streamlit](https://docs.streamlit.io/) 👑 for UI and interaction.
- **Hosted locally** with [Ollama](https://ollama.com/) 🦙.



## Authors

- [Mane Reyes](https://github.com/thepurpleoni)


## Installation

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd <repo_dir>
```


Install virtualenv if you don't have it.
```bash
  pip install virtualenv

```
Then, create a virtualenv inside the project directory.
```bash
  mkidr <repo_dir>
  cd <repo_dir>
  python<version> -m venv <virtual-environment-name>
```

And activate the venv.
```bash
  source env/bin/activate
```

Finally, install the requirements.
```bash
  pip install requirements.txt

```
## Walkthrough

Once you clone the repo inside your directory and created the venv with all the packages and libraries, you only need to run this command.
```bash
  streamlit run main.py
```
A brief explanation of the different parameters
- **Model** : Here you select the LLM model, since the models run locally, you will need to change the values of the st.selectbox deppending of the ones you have installed.
- **Temperature** : The temperature of the model. Increasing the temperature will make the model answer more creatively.
- **System Prompt** : Give the LLM a context, a role to do, explain "who" is him and "what" is going to do.
- **User** : Give the LLM a task based on the context you gave to it in the System Prompt.
- **Mood Response** : Choose a mood for the LLM to generate a its response, you can use this to test their sentient level.
- **Language** : Choose a language for the output response, you can use this to test the LLM text generation on many languages.



