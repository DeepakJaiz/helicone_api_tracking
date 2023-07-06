# helicone_api_tracking

### Aim 
We use helicone to track our token use by our LLM and also track how much we spend on our LLM.

### Prerequist
You required Phython in your system to get you can follow this (https://www.python.org)<br/>
OpenAi API key required to get you can follow this link (https://platform.openai.com/account/api-keys)<br/>
Install Jupyter Notebook to run the code.<br/>

### How to use Helicone
- First register on helicone and generate your api key. For register you can follow this link(https://www.helicone.ai/).
- Then use helicone api key in your LLm where you call within header with "Helicone-Auth" as key.
- If more than one person using this api key then you have to add one more field in header i.e "Helicone-User-Id" with any id so that we can track each user usages.
