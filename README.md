# Exno.4-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
3. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
4. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
5. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
6. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
7. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Result: The various types of Prompts are executed successfully.
 **1. Direct Instruction Prompts**
Objective:
Guide the chatbot to respond concisely to customer inquiries.

Prompt Pattern:
Prompt:
"When a customer asks for the status of their order, reply with:
'Your order is currently being processed and will be delivered by [date].'"

Expected Outcome:

The chatbot will respond immediately and clearly, giving the user exactly the information requested.

Minimizes unnecessary conversation or confusion.

Ensures quick resolution of common, simple queries.

Example Interaction:
Customer: "What's the status of my order?"
Chatbot: "Your order is currently being processed and will be delivered by April 27th."

Evaluation Criteria:

Clarity: Response directly addresses the question.

Brevity: Limited to essential information.

Consistency: Uniform replies to similar questions improve user trust.
**2. Contextual Prompting**
Objective:
Incorporate specific context from prior user interactions to provide more personalized and accurate responses.

Prompt Pattern:
Prompt:
"If the customer previously mentioned that they haven’t received their order, say,
'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

Expected Outcome:

The chatbot demonstrates awareness of the ongoing conversation, improving user experience.

Users feel heard and understood, leading to increased satisfaction and trust.

Responses are more relevant to the current concern rather than generic replies.

Example Interaction:
Customer (earlier): "I placed my order last week but still haven’t received it."
Customer (later): "Can you help me with this?"
Chatbot: "I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly."

Evaluation Criteria:

Context Awareness: Ability to recall and reference previous user inputs accurately.

Relevance: Response aligns closely with the user’s ongoing concern.

User Engagement: Creates a more natural, conversational flow, simulating a human-like interaction.
**3. Persona-Based Prompting**
Objective:
Design the chatbot to adopt a specific persona, making the interaction more engaging and personable.

Prompt Pattern:
Prompt:
"Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as
'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

Expected Outcome:

The chatbot interacts in a warm, approachable manner, enhancing the customer experience.

Encourages users to feel more comfortable expressing concerns or asking questions.

Builds rapport and humanizes the support process.

Example Interaction:
Customer: "I’m not sure how to return a product."
Chatbot: "Hey there! No worries, I’ve got your back. Let’s walk through how to return that item together—it’s pretty easy!"

Evaluation Criteria:

Tone Consistency: Responses maintain a consistently friendly and conversational tone.

User Comfort: Users are more likely to engage openly due to the relaxed and supportive demeanor.

Brand Alignment: Persona matches the brand’s voice, reinforcing identity and trust.
 **4. Few-Shot Prompting**
Objective:
Teach the AI how to respond to customer queries by providing a few examples, enabling it to generalize and respond effectively to similar questions.

Prompt Pattern:
Prompt:
"Here are some examples of how to handle technical questions:

'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'

'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

Expected Outcome:

The chatbot learns patterns from the provided examples and applies similar logic to new queries.

Reduces the need for manual scripting of every possible scenario.

Supports scalable training of the AI across multiple issue types.

Example Interaction:
Customer: "My app keeps crashing."
Chatbot: "That sounds frustrating! Have you tried clearing the app’s cache or reinstalling it? If it still crashes, let me know what device you're using so I can help further."

Evaluation Criteria:

Pattern Recognition: AI successfully mimics the logic and tone used in the examples.

Adaptability: Able to generalize and apply responses to similar but not identical queries.

Response Quality: Suggestions are practical, relevant, and easy for the user to follow.
 **5. Chain of Thought Prompting**
Objective:
Use a step-by-step reasoning approach to guide users through resolving more complex or technical issues, improving problem-solving clarity and accuracy.

Prompt Pattern:
Prompt:
"When a customer reports their laptop overheating, guide them through the following steps:

Ask if they are using the laptop on a soft surface.

Suggest moving the laptop to a flat, hard surface for better airflow.

Ask if they’ve cleaned the vents recently.

Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"

Expected Outcome:

The chatbot walks the user through a logical sequence of diagnostic steps.

Encourages user participation in the troubleshooting process.

Breaks down complex problems into manageable parts, reducing user overwhelm.

Example Interaction:
Customer: "My laptop fan is making a loud noise."
Chatbot:
"Let’s figure this out step by step:

Are you using your laptop on a soft surface like a bed or couch?

Try placing it on a hard, flat surface to help with airflow.

Have you checked and cleaned the air vents recently? Dust buildup can cause fan noise.

You might also try restarting the laptop—sometimes a simple reboot can help the system reset."

Evaluation Criteria:

Stepwise Reasoning: Follows a logical progression of questions and suggestions.

User Empowerment: Guides users to troubleshoot independently where possible.

Resolution Likelihood: Steps are relevant and likely to lead to issue resolution or better diagnosis.
**6. Instruction with Constraints**
Objective:
Instruct the chatbot to assist users while adhering to specific constraints such as limited response length and simplified language. This helps ensure clarity and accessibility across a wide range of users.

Prompt Pattern:
Prompt:
"Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example,
'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

Expected Outcome:

The chatbot delivers concise, easy-to-understand answers that are quick to read.

Avoids overwhelming the user with too much information or technical terminology.

Maintains a helpful, customer-friendly tone while meeting operational constraints.

Example Interaction:
Customer: "Where is my order?"
Chatbot: "Your order is on the way and should arrive by April 28th. Let us know if you need anything else—we’re happy to help!"

Evaluation Criteria:

Brevity: Stays within the 50-word limit.

Accessibility: Avoids technical language or industry jargon.

Tone: Clear, reassuring, and customer-friendly.
 **7. Reflective Prompting**
Objective:
Ensure that the chatbot reflects the user's query back to them before providing a response. This approach confirms understanding, reduces misunderstandings, and enhances clarity in communication.

Prompt Pattern:
Prompt:
"When a customer asks for help, first reflect their question back to them. For example, if they ask
'How can I reset my password?' respond with
'You're asking how to reset your password, correct? Here’s how you can do it.'"

Expected Outcome:

The chatbot confirms the user's request before proceeding, reducing chances of miscommunication.

Enhances user trust by showing attentiveness and comprehension.

Establishes a more conversational and thoughtful tone.

Example Interaction:
Customer: "How do I update my delivery address?"
Chatbot: "You're asking how to update your delivery address, correct? Here’s how you can do it: Go to your account settings and click on 'Addresses' to make the changes."

Evaluation Criteria:

Clarity: The chatbot clearly rephrases the user's question before answering.

Accuracy: Reduces error in interpreting user intent.

User Assurance: User feels acknowledged and understood before receiving instructions.





# Result: Thus the Prompts were exected succcessfully .

