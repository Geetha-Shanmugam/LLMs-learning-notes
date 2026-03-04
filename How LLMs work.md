I usually make study notes inorder to recall, remember what i learn to comfort myself

Also I always feel writing notes boost my confidence in understanding the concepts

So today I have learnt few things about how LLM actually work.. before understanding how to test AI models, it is mandatory to understand how AI models actually functions or some foundational AI concepts.. so that we can effectively test the AI models.

LLM has no memory
-------------------
1. Generally LLM's has no memory and it does not store anything whatever you give as input prompt and its outputs.
     Let's say - you start conversation by giving your first input prompt in chatgpt or gemini or any model and it gives some output responses as output.
                 and then you ask next question and it gives responses

    So here you might think LLM store the first prompt and response in memory and answer the second prompt accordingly.. But No.
2.   What happens at the backend is, LLM use the complete conversation history (which means here first input prompt and response) inorder to respond to the second prompt
     so, if you are inputing 100th prompt, LLMs take the 99th prompt inputs and responses and understand the complete conversation history then respond to 100th prompt.
   Each time LLM go through the complete conversation history inorder to respond.. So LLM has NO memory



 

Large Language models (LLM) are trained using billions and billions of data.. Let's say  
