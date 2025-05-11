# Prompt-Engineering-4.1
# EXP 4 Scenario-Based Report Development Utilizing Diverse Prompting Techniques- Lab Scenario: Smart Health Assistant System
# Description: 
## Background:
You are part of a development team working on an AI-based Smart Health Assistant named "MediGuide" that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

## Objective:
Develop a scenario-based report that demonstrates how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts) can be used to optimize MediGuide’s responses in different use cases.

# Algorithm:1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries. Prompt Pattern: Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'" 2. Contextual Prompting Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction. Prompt Pattern: Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'" 3. Persona-Based Prompting Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging. Prompt Pattern: Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'" 4. Few-Shot Prompting Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations. Prompt Pattern: Prompt: "Here are some examples of how to handle technical questions: 'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.' 'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?' Now, respond to: 'My app keeps crashing.'" 5. Chain of Thought Prompting Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues. Prompt Pattern: Prompt: "When a customer reports their laptop overheating, guide them through the following steps: Ask if they are using the laptop on a soft surface. Suggest moving the laptop to a flat, hard surface for better airflow. Ask if they’ve cleaned the vents recently. Recommend restarting the device to see if the issue persists. Now, solve: 'My laptop fan is making a loud noise.'" 6. Instruction with Constraints Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone). Prompt Pattern: Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'" 7. Reflective Prompting Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings. Prompt Pattern: Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'" Result: The various types of Prompts are executed successfully.

# Output:
# TECHTRAIL BOT

# STRAIGHT FORWARD PROMPT
```

Prompt 1 – “Subscribe to Tech Updates”
Response:
Sure! I can get you subscribed to the latest CS and tech updates. Please provide the following details:
1.Your full name:
2. Preferred topics (e.g., AI, Web Development, Cybersecurity):
3. Email or mobile number to receive updates:
4. How frequently would you like updates? (Daily, Weekly, Monthly):
Once I have this info, I’ll get you subscribed to curated tech news and insights!

Prompt 2 – “Tech Emergency Support”
Response:
I’m here to help with your technical issue. Please describe your problem clearly (e.g., system crash, code error, deployment failure). I’ll guide you through basic troubleshooting or redirect you to support resources.
If this is a company network or cybersecurity emergency, please report it to your system administrator immediately.

Prompt 3 – “View Latest Trends”
Response:
To show you the latest trends in tech, I just need the following:
1.Area of interest (e.g., Cloud Computing, Data Science, DevOps):
2. Preferred content type (Articles, Videos, Tools, etc.):
3. Level (Beginner, Intermediate, Advanced):
Once I get this info, I’ll show you the most relevant and recent trends in your chosen field.

Prompt 4 – “Check Mentor Availability”
Response:
Sure! I can help you check tech mentor availability. Please provide the following:
1.Field or topic you'd like mentorship in (e.g., ML, DSA, Web Dev):
2. Preferred date and time:
3. Do you have a specific mentor in mind? (Yes/No – If yes, please provide name):
4. Mode of mentorship (Online or In-person):
Once I have these details, I’ll check and confirm availability for you.

Prompt 5 – “Suggest a Project Idea”
Response:
Absolutely! Let me help you with a project idea. Please provide the following details:
1.Area of interest (e.g., Web Development, AI, IoT, Blockchain)
2.Your current level (Beginner, Intermediate, Advanced)
3.Duration you can commit (e.g., 1 week, 1 month)
4.Are you working solo or with a team?
Once I have that, I’ll suggest a relevant, achievable project idea.

Prompt 6 – “Debug My Code”
Response:
I can assist you with that! Please provide:
1.Programming language
2.The piece of code you're stuck on
3.A short description of the issue
I’ll review and suggest corrections or improvements.

Prompt 7 – “Learn a New Technology”
Response:
Awesome! Tell me what you're interested in:
1.Technology/topic (e.g., Docker, React, TensorFlow)
2.Your current knowledge level
3.Preferred learning style (Video, Articles, Hands-on Projects)
I'll provide you with a beginner-friendly roadmap and top resources.
```

# TABULAR FORMAT PROMPT
```
Prompt 1:
User Prompt
Tech Emergency Support
View Latest Trends
Check Mentor Availability
Subscribe to Tech Updates
Response –
User Prompt	Bot Response
Tech Emergency Support	"Please describe your issue (e.g., system crash, network failure, deployment error), and I’ll guide you with quick solutions or redirect to support."
View Latest Trends	"Tell me your interest area (e.g., AI, Web Dev, Cloud), and I’ll show you the latest articles, tools, and updates trending in that field."
Check Mentor Availability	"Please provide your preferred tech field, time, and consultation mode (online/in-person), and I’ll check mentor availability for you."
Subscribe to Tech Updates	"Provide your name, contact, topics of interest, and frequency (daily/weekly), and I’ll subscribe you to curated tech updates."

Prompt 2:
S.No	User Prompt
1	Best Time for Mentorship
2	Procedure to Join a Webinar
3	Tech Emergency Contact
Response –
S.No	User Prompt	Bot Response
1	Best Time for Mentorship	"Mentorship sessions are usually available between 6:00 PM and 9:00 PM on weekdays."
2	Procedure to Join a Webinar	"Register through the link provided in the update. Use your email to get a reminder and access link."
3	Tech Emergency Contact	"For urgent tech issues, contact techsupport@yourorg.com or call 1800-TECH-911."


Prompt 3:
User Prompt
Suggest a Project Idea
Debug My Code
Learn a New Technology
Subscribe to Tech Updates
Response –
S.No	User Prompt	Bot Response
1	Latest Tech Events	"Check out HackSummit 2025 (May 20–22) and DevOpsDays (June 5)."
2	Internship Opportunities	"You can apply at Internshala, HackerEarth, and LinkedIn's Student Programs."
3	Trending CS Fields	"Top fields: AI, Cybersecurity, Cloud Computing, and DevOps (2025 trends)."
```

# PRECEDING QUESTION PROMPT
```
User prompt 1:
"Subscribe to Tech Updates"
Response:
"To subscribe, please provide your Full Name, Email or Phone Number, Preferred Topics, and Frequency of Updates."

User prompt 2:
"Name – Rahul
Number – 984XXXXX
Topics – AI, Cybersecurity
Frequency – Weekly"
Response:
Got it! You've selected weekly updates on AI and Cybersecurity.

User prompt 3:
"Send via Email"
Response:
Your subscription is now active. Updates will be sent to your email weekly. You can manage preferences anytime.
Would you also like access to our latest free eBooks?


User prompt 4:
"Yes, send me the eBooks too."
Response:
Great! The latest tech eBooks will be sent to your email shortly. Check your inbox for download links and enjoy exploring!

User Prompt 5:
"Suggest a Project Idea"
Response:
"Tell me your area of interest, skill level, and timeframe. I’ll suggest a suitable idea."

User Prompt 6:
"Area – AI
Level – Intermediate
Duration – 1 month
Solo"
Response:
Great! I suggest:
"AI Chatbot for Student Support" – Build a chatbot using Python and NLP libraries to assist students with academic queries.

User Prompt 7:
"Can I get the tools required?"
Response:
Sure! You'll need:
Python
NLTK or spaCy
Flask or Streamlit (for web interface)
Git (for version control)

User Prompt 8:
"Send me a GitHub starter template."
Response:
Here’s a helpful GitHub template to get started:
AI-Student-Bot Template on GitHub
Let me know if you'd like documentation or deployment help too.
```
# Result




