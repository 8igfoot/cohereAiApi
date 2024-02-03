# CohereAI API

A simple Google Apps Script used to call Cohere Platform API with a prompt. 

Usage:

`gCcAi(prompt,200);`

Where <prompt> is the question text you want to ask Cohere Platform API and 200 represents the max amount of tokens you want to use for this activity (200 is standard). For this to work you need a Cohere AI account and sign up for Google Apps Scripting, both of which are free. Here is how to get started:

- [Google Apps Scripting](https://www.google.com/script/start/) - Create automations and web services
- [Cohere AI API](https://cohere.com) - Access AI web service API

### Example output:

`gCcAi('What is bigfoot?',200);`

Output:

>Bigfoot, also known as Sasquatch, is a mythical ape-like creature that is said to inhabit forests in the Pacific Northwest region of North America. It is an anthropomorphic creature with enormous footprints. American folklore has different variants of the bigfoot legend, which differs in descriptions of the creature from region to region. 

>In the 21st century, mainstream science classifies bigfoot as a cryptid, a creature whose existence is disputed and lacks scientific proof. Scientists have found thousands of bigfoot-like footprints, but the sightings of the creature are often subjective due to the dense forests of the Pacific Northwest. Thus, making it a difficult area to study wildlife with so many other animals in the area. 

>The legend of Bigfoot persisted throughout the 20th century and remains a popular cultural icon today. Would you like me to go into more detail about the cultural significance of Bigfoot

### Useability

|Function:|Result:|
|---|---|
|Signup|🟩 Simple|
|API key setup|🟩 Created on opening account|
|Available code examples|🟥 None of the curl examples work|
|Any issues|🟨 Token/daily limits can prevent any legitimate testing|
|Execution time|🟨 5695.0 milliseconds|
