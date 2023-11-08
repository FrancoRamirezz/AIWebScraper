# WebScraper, Langchain and OpenAI

## Installations 🤖:
```bash
pip install openai,
pip install langchain,
pip install playwright
from langchain.memory import ConversationBufferWindowMemory
from langchain.agents import load_tools, AgentType, initialize_agent
from langchain.document_loaders import AsyncChromiumLoader
from langchain.document_transformers import BeautifulSoupTransformer
from langchain.document_loaders import AsyncHtmlLoader
from langchain.document_loaders import WebBaseLoader

# Common issues 🎮
if there is an issue with the event loop, it could be caused by Google Colab, but it depends on the environment that you are running on.
For example,
```bash
async def webScrape():
  pass

# for proxy uses:
use the following code 
import request 

set_proxies = {
"https": "http://proxy1.example.com:8080",
"https": "https://proxy2.example.com:8443"",
}
response = requests.get("https://www.example.com", set_proxies=set_proxies)
print(response.status_code)
### the status code will tell us if it was successful or not 


# future use: 
i will try to use Streamlit to make an interface.
