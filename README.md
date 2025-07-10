<div align='center'><img style="width:30%" src='https://github.com/user-attachments/assets/a912d643-cab1-49b1-aad9-8fc7dc66a8e7'/></div>


An **AI Agent** is a system that perceives its environment, processes information, and takes actions to achieve a goal.  
It often uses **machine learning** or **rule-based logic** to make decisions and act intelligently.  
Examples of AI Agents include **chatbots** (e.g., ChatGPT), **recommendation engines** (e.g., Netflix), and **automated workflow bots**.

**n8n** is a **workflow automation tool** that allows users to automate tasks and integrate various APIs without extensive coding.  
It provides a no-code/low-code interface, flexible workflow creation, and seamless integration with the OpenAI API and many other services — making it ideal for AI automation.

![image](https://github.com/user-attachments/assets/94068197-9faf-4212-bd6b-953d1b95d8e6)

The workflow listens for incoming chat messages using the **When chat message received** node.  
The message is sent to the **AI Agent**, which uses the **Groq Chat Model** to generate a response and the **Simple Memory** node to remember previous messages.  
When a user asks something (e.g., *Who is the Prime Minister of India?*), the workflow replies with a complete answer, leveraging both the AI model and memory.
This demonstrates how you can use **n8n + AI Agent + Memory** to create intelligent conversational bots with little to no coding.
