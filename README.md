# CohereAI API

A simple Google Apps Script used to call Cohere Platform API with a prompt. 

Usage:

`gCcAi(prompt,null);`

Where <prompt> is the question text you want to ask Cohere Platform API. For this to work you need a CoralAI account and sign up for Google Apps Scripting, both of which are free. Here is how to get started:

- [Google Apps Scripting](https://www.google.com/script/start/) - Create automations and web services
- [Cohere AI API](https://cohere.com) - Access AI web service API

NOTE: Unlike mainstream AI API's like Google Gemini and OpenAi, Cohere's "free" API is extremely limited, such that you can run out of free tokens quickly, at which point it just returns a null string.

### Example output:

`gCcAi('What is bigfoot?',null);`

Output:

>Bigfoot is a legendary creature said to inhabit the forests of the Pacific Northwest, Western Canada, and the United States. It is described as an oversized, hairy, bipedal humanoid, covered in thick fur often described as reddish-brown.

>The name Bigfoot is a commonly used colloquial term, but the creature is also known as Sasquatch, Yeti, or Abominable Snowman, among other names.

>The existence of Bigfoot is largely considered to be a myth, with a lack of credible and scientific evidence. However, the legend of Bigfoot is a popular cultural phenomenon, featuring prominently in folklore, literature, film, and television. The myth has also sparked interest in cryptozoology, the academic study of such legends.

>Some people claim to have encountered Bigfoot, describing it as a large, powerful, and intelligent being. Others suggest that these sightings can be explained by misidentification of natural phenomena, such as wind and weather, or hoaxes.

>Bigfoot is a fascinating part of our cultural heritage and an enduring source of fascination and wonder.
