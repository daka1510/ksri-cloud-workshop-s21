## Build a Spoken Translator
In this exercise you will learn how to create a spoken translator with the aid of [Node-RED](https://nodered.org/) and [IBM Watson products](https://www.ibm.com/watson/products-services).

### Steps
1. [Create the Watson AI service instances](../guidelines/create-watson-services)
2. [Connect the Watson AI Services to the Node-RED App](../guidelines/connect-watson-services)
3. Follow steps 5, 6, 7 from the [IBM Developer](https://developer.ibm.com/) tutorial 
   - [Build a spoken universal translator using Node-RED and Watson AI services](https://developer.ibm.com/technologies/artificial-intelligence/tutorials/build-universal-translator-nodered-watson-ai-services/)
   - feel free to update the language settings such that your translator translates from "German" to the language of your choice
4. Experiment on your own. 
  - What other use-cases can you think of?
  - Are there other [prebuilt services](https://cloud.ibm.com/catalog?search=label%3Alite%20label%3Aibm_created&category=ai#services) that could help?

Special thanks to [John Walicki](https://developer.ibm.com/technologies/artificial-intelligence/tutorials/build-universal-translator-nodered-watson-ai-services/) who originally published the [tutorial](https://developer.ibm.com/technologies/artificial-intelligence/tutorials/build-universal-translator-nodered-watson-ai-services/) we used as a basis.


### Hints 
When running Node-RED on your local workstation, be aware of the below differences.
- You have to manually install the [node-red-node-watson](https://flows.nodered.org/node/node-red-node-watson) flows via `Menu > Manage palette > Install`.
- You cannot connect the Watson AI Services as instructed above. Instead, check out the configuration options of the Watson Nodes and fill in endpoint and API keys.
