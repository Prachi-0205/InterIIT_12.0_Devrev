# DevRev - AI Agent 007 - Inter IIT Tech Meet 12.0

GPT-4-turbo and GPT-3.5-turbo access is required.

Run the script on a linux system preferably.

## Data Files

- `tools.json` - The JSON file containing the list of pre-existing tools.
- `examples.json` - The JSON file containing the list of pre-existing examples.

## Steps to run the Final Script on the interface

- Create a Python environment with Python version 3.10.12
- Install all the required packages using the following command -

  `pip install streamlit==1.27.0 sentence-transformers hnswlib openai==1.4.0 streamlit_nested_layout numpy`

- Replace the API_KEY in `utils.py` (line 18) and `main.py` (line 11) with your OpenAI API key.
- After installations, to start the interface, run `main.py` using the command -

  `streamlit run main.py`

## Steps to run the Final Script on Colab (only the backend)

- Find the link of colab [here](https://colab.research.google.com/drive/1L3A2NH4voeIIkwme2DUA89xv7CvqnAFb?usp=sharing).
- Instructions to run the colab notebook are present in the notebook.
- Make sure to replace the API_KEY (first block) with your own OpenAI API key.
- Run all the cells sequentially before executing any query.
