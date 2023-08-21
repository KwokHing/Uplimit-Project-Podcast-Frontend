## [Uplimit](https://uplimit.com/course/building-ai-products-with-openai) Project: Podcast Summarizer

In this project, an LLM app was built to summarize a podcast episode, identifies the podcast guests and attempts to retrieve the guest's public information from wikipedia, and identifies key highlights using OpenAI ChatGPT and prompting techniques. Cloud deployment provider [Modal](https://modal.com/) was used to convert the information extraction function into a cloud on demand service, while the front-end interface was deployed on [Streamlit](https://streamlit.io/)

#### The solution was developed in three parts: ####

**Part 1**: Use a large language model from OpenAI to build the information extraction functionality, paired with a speech-to-text model for transcribing the podcast.

**Part 2**: Use a simple cloud deployment provider to easily convert the information extraction function to run on demand – This would be the app backend.

**Part 3**: Use ChatGPT from OpenAI as your coding assistant to create and deploy a front-end that allows users to experience the end-to-end functionality.

Try it [here](https://uplimit-project-podcast-frontend.streamlit.app/)

## Getting started
Open `Uplimit_Week1_Summarise_Podcast_GPT.ipynb` on Google Colab. The notebook consists of further technical details.


