# Story Wizard

Welcome to our interactive story teller project! We created this app as part of a hackathon with one goal in mind: to make storytelling more engaging and fun for children. We all know how much kids love stories, but it can be a challenge for parents and teachers to keep up with their constant demand for new ones. That's where our project comes in – it provides a solution to this problem by offering a vast library of pre-made stories on a variety of topics, as well as the ability to generate new stories based on children's interests.

But that's not all – we've also added an exciting new feature to our app that allows children to ask follow-up questions about the stories. The app will then narrate the answers, creating an interactive experience that encourages curiosity and engagement.

Our interactive story teller is designed to be incredibly user-friendly, with a simple interface that children can easily navigate. Whether they want to browse through pre-made stories or generate a new one based on their interests, the app provides a seamless experience. And with clear, engaging narration and accompanying visuals, children can fully immerse themselves in the story.


## Tech-stack

#### Frontend:

- ReactJS
- Tailwind CSS

#### Backend:

- Python
- Flask
- GPT, Stable Diffussion, Google text-to-speech API

## Installation Instructions

Run the following commands in the given order to get the front end running.

- `git clone https://github.com/sumukhmg/Story-wizard`
- `python -m venv`
- `source venv/bin/activate`
- `pip install -r requirements.txt`
- Generate your API key for OPENAI from [here](https://platform.openai.com/account/api-keys) and StabilityAI from [here](https://beta.dreamstudio.ai/account)
Add the API keys to the .env file in the following format

```
OPENAI_API_KEY=<key>
STABILITYAI_API_KEY=<key>
```

- Generate the google cloud credentials file from [here](https://cloud.google.com/text-to-speech/docs/before-you-begin) and save the JSON file as `service.json` in the root of the repository.

## Libraries and Dependencies

- Flask
- Flask CORS
- Pandas
- OpenAI
- Google cloud text to speech
- requests
- base64

#screenshots
![image](https://github.com/sumukhmg/Story-wizard/assets/83581264/a8a17a40-85fe-491c-ae79-55c838327201)
![image](https://github.com/sumukhmg/Story-wizard/assets/83581264/5ab3bd97-b3c8-4c13-8b64-94656190daa5)
![image](https://github.com/sumukhmg/Story-wizard/assets/83581264/312539d1-326d-43e3-99c7-e19e22580f53)
