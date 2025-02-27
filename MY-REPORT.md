![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

Requirement Analysis of Prompt Engineering Techniques for generating a discord chatbot for Study Companion

"A Discord bot designed to assist students by answering queries, fetching additional information through web search, and utilizing GenAI capabilities to personalize and enhance responses."


* Authors: [Pranay Babu Totakura, Sai Vamshi Adire, Marnani Lourd Akash]
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

"How can we harness the power of GenAI and web search to create a supercharged Discord bot that offers personalized, intelligent tutoring for students, making learning faster and more engaging?"


## Arguments

#### What is already known about this topic

* You could use AI-powered chatbots to provide immediate, on-demand tutoring and answer student queries, achieving faster and more personalized learning experiences.
* The challenges of building an intelligent, interactive bot involve accurately understanding diverse student questions and providing reliable, contextually relevant responses in real-time.
* The possibility of integrating web search to enhance the bot’s knowledge base could help it stay up-to-date and provide information that isn't explicitly programmed into it, thus improving the quality and depth of responses.

#### What this research is exploring

* We employ generative AI techniques, particularly large language models, to enhance a Discord bot's ability to provide personalized, on-demand tutoring.
* We are building an intelligent study companion bot that answers student queries, fetches additional information via web search, and adapts to individual learning needs.
* We are exploring the integration of web search capabilities to allow the bot to retrieve up-to-date information, improving response quality and accuracy in real-time.

#### Implications for practice

* It will be easier to provide students with personalized, on-demand tutoring by automating responses and adapting to their individual needs.
* It will optimize the study process by delivering accurate, relevant information quickly, allowing students to focus on learning rather than searching for resources.
* We will better understand how AI can enhance student engagement and improve learning outcomes through dynamic, real-time interaction.

## Research Method:

In the research process, the following methodologies and prompt engineering techniques were employed to build and optimize the Study Companion Discord Bot:

1. Problem Definition:
The primary goal of the project was to design a personalized tutoring chatbot capable of providing real-time, intelligent assistance to students. To achieve this, we focused on developing a system that could:

    Answer academic queries accurately.
    Fetch additional information from external sources via web search.
    Use Generative AI techniques to personalize the learning experience.
2. Prompt Engineering Techniques:
Various prompt engineering techniques were crucial in improving the bot’s performance and response quality. The following strategies were applied during the development process:

Few-Shot Prompting:
To train the bot to respond to various academic queries, we implemented few-shot prompting. This involved providing a few examples of how to handle specific queries, followed by the bot’s expected responses. For instance, in the case of math or science queries, the bot was trained to respond concisely and accurately using examples of similar questions.

Zero-Shot Prompting:
In scenarios where explicit training examples weren’t available, we leveraged zero-shot prompting to guide the bot’s responses. This technique enabled the bot to generate reasonable answers to questions that it had not specifically seen during training, ensuring versatility in handling unfamiliar queries.

Meta Prompting:
The meta-prompting technique was applied to improve the bot's ability to generate a structured Requirement Analysis Document for the project. By including a meta-prompt that defined the bot's task, we directed it to generate responses in a more systematic and organized format. This approach ensured the bot was able to synthesize clear, high-level documentation, including functional and non-functional requirements, user stories, and system components.

3. Model Selection:
We utilized the Ollama platform with the Llama3.2 model to implement these techniques. The model was selected for its ability to handle complex natural language processing tasks and its flexibility in supporting a variety of prompt engineering techniques.

4. User Testing and Feedback:
A user-centered design approach was taken to ensure that the bot met the needs of the students. During the testing phase, real students interacted with the bot, providing feedback on its performance, the clarity of its explanations, and the relevance of its answers. The feedback was used to further refine the bot’s functionalities, making it more efficient and user-friendly.


# Results
Through the research process, we achieved significant progress in building a highly functional and effective Study Companion Discord Bot. The following table summarizes the key results based on the various prompt engineering techniques we applied, focusing on Accuracy, Completeness, Consistency, and Efficiency:
1. Accuracy:
The use of few-shot prompting and meta prompting ensured high accuracy in the bot’s ability to answer academic queries and generate structured documentation. Zero-shot prompting provided reliable responses even for queries that the bot hadn't explicitly encountered.

2. Completeness:
The bot was able to deliver comprehensive responses due to the prompt engineering techniques applied, especially with structured few-shot prompting and prompt template prompting. In scenarios where new information was needed, the bot leveraged web search integration to provide complete answers.

3. Consistency:
The consistency of responses was optimized by employing meta prompting and prompt template prompting, which ensured that the bot adhered to a structured approach and was less likely to generate inconsistent or incomplete answers. Zero-shot prompting exhibited slightly less consistency, especially in more complex or nuanced queries, but it still maintained an acceptable level of reliability.

4. Efficiency:
Efficiency was improved through the use of prompt templates and zero-shot prompting. These techniques allowed the bot to handle queries rapidly without the need for extensive pre-training. Additionally, the meta prompting technique enabled fast generation of Requirement Analysis Documents, ensuring the process was both time-efficient and effective.

# Further research
Based on the current exploration of prompt engineering techniques, the next steps in research could focus on refining these techniques and exploring their applications in more complex and diverse scenarios. Here are some potential directions for further research:

1. Hybrid Prompt Engineering Techniques:
Investigate combining multiple prompt techniques (e.g., Chain of Thought with Few-Shot or Memory-Augmented with Self-Consistency) to improve accuracy and consistency across diverse tasks, especially for complex or dynamic user queries.

2. Dynamic Memory Management:
Explore how memory-augmented techniques can be optimized to handle long-term interactions without compromising efficiency. Investigate how memory management systems can be designed to prioritize relevant context while discarding outdated or irrelevant information.

3. Real-World Application Testing:
Conduct further testing of the Study Companion Discord Bot with real students to validate the effectiveness of the prompting techniques in educational settings. Analyze how the bot can adapt to a wide range of subjects and student needs while maintaining accuracy and personalization.

* New Ideas Proposals:
1. Multimodal Prompting for Richer Interactions, Cultural and Linguistic Adaptability, Cross-Domain Adaptability, Integration with Augmented Reality (AR), etc.,. are some of the new ideas which we bring to proposal
2. Multimodal Prompting enhances AI interactions by integrating images, voice, and text for richer responses. Cultural and Linguistic Adaptability tailors the AI to diverse users, while Cross-Domain Adaptability connects various subjects for a broader learning experience. Integrating Augmented Reality (AR) brings immersive, hands-on learning, enriching student engagement and comprehension. These ideas aim to create an interactive and inclusive educational environment.