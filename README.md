# Chatbot_COVID
Chatbot for COVID-19 information 


### Step1
Create virtualenv and install rasa using this guide https://rasa.com/docs/rasa/user-guide/installation/ 

### Step2

```
rasa init
```

for initialization of the directory structure required for rasa

### Step3
Update domain.yml for actions, intents and responses.
Update data/nlu.md for all the intents used in the chatbot 
Update data/stories.md for all the conversations required for user and bot

### Step4


```
rasa train
```

This command will train the model and saves into the models/ folder

### Step5

```
rasa x -m models/xxxx.tar.gz
```

For starting rasa x server (Browser version)

### Step 6
```
rasa shell
```

For starting cmd version.

