# AI Assistant Impact On Student Success
## Project Overview
### Project Purposes
&nbsp;&nbsp;&nbsp;&nbsp; This project aims to conduct analysis of [kaggle dataset](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic) on AI assistant usage among students especially on daily life. The goal is to measure the impact of AI on academic success and learning effectiveness, and to identify the most beneficial usage patterns. The findings will be used to formulate concrete recommendations for educational institutions and students to optimally integrate AI into their learning process. 

### Background of the study
&nbsp;&nbsp;&nbsp;&nbsp; Artificial Intelligence (AI) has been evolving rapidly in recent years, enabling machines to perform wide range of human tasks from simple to highly complex task. One primary reason AI gaining traction because of its efficiency in handling repetitive and routine tasks without requiring extensive resources. These capabilities have positioned AI as a higly valuable solution across various industries including education. In the context of higher education, AI-powered assistant are becoming encreasingly significant in supporting students throughout their academic journey.

&nbsp;&nbsp;&nbsp;&nbsp; With the growing reliance on digital learning environments, students often encounter difficulties in understanding complex concepts. AI assistant such as ChatGPT, Google Bard, and IBM Granite are developed to address this gap by delivering immediate responses, simplifying difficult topics, and offering consistent feedback without the need for human tutors. This level of accessibility and responsiveness has the potential to significantly enhance students’ academic performance and overall learning experience (Luckin et al., 2016). 

&nbsp;&nbsp;&nbsp;&nbsp; By applying statistical methods to [this dataset](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic), the project will move beyond general observations to pinpoint specific correlations and predictive relationships. The findings will provide educational institutions with a concrete basis for developing strategies that effectively integrate AI into their learning environments, fostering a culture of responsible use while maximizing student success.

### Dataset Data Understanding
Dataset : AI Assistant Usage in Student Life - [Kaggle](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic)

There is <b>10000 rows</b> of data and <b>11 columns<b> in the dataset. 

Dataset Structure is:
|       Column       |                            Description                              |
| ------------------ | ------------------------------------------------------------------- |
|      SessionID     | Unique session identifier.                                          |
|     StudentLevel   | Demographic academic level : High School, Undergraduate, Graduate.  |
|      Discipline    | Field of study : e.g., CS, psychology, etc.                         |
|     SessionDate    | Date of the session.                                                |
|   SessionLengthMin | Length of AI interaction in minutes.                                | 
|     Total Prompts  | Number of prompts/messages used.                                    |
|       TaskType     | Task being worked on (e.g., Coding, Writing, Research).             |
| AI_AssistanceLevel | 1–5 scale on how helpful the AI was perceived to be.                |
|     FinalOutcome   | What the student achieved: Assignment Completed, Idea Drafted, etc. |
|      UsedAgain     | Whether the student returned to use the assistant again.            |
| SatisfactionRating | 1–5 rating of overall satisfaction with the session.                |

### Problem Statement
&nbsp;&nbsp;&nbsp;&nbsp; The focus problems to be analysis are:
1. Academic Correlation: To what extent does the frequency of AI assistant use influence a student's self-reported Effectiveness Score? Is there a direct relationship between how often a student engages with AI and their perception of its usefulness?
2. Usage Patterns  and Demographic Impact : How do specific demographic factors (e.g., Major, Year of Study) or usage patterns correlate with a student's perceived Effectiveness Score? We will identify if certain student cohorts utilize and benefit from AI assistants more than others.
3. Tasks-Specific Benefits : Do all academic tasks benefit equally from AI assistance? How does the specific Purpose of Use of an AI assistant (e.g., Homework help, Concept explanation) correlate with a student's final perceived Effectiveness Score? We will identify which tasks are most effectively supported by AI and provide insights into the expected outcomes for each. 

### Approach 
&nbsp;&nbsp;&nbsp;&nbsp; This project uses LLM by IBM (IBM-granite-3.3-8b-instruct). By using LLM, model expected to analyze all problem that had been stated above. Kaggle dataset is used for this project https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic. The analysis process of this project will follow systematic flow, from data analysis to visualization and conclusion.



## Insight & Findings

## AI Support Explanation
&nbsp;&nbsp;&nbsp;&nbsp; This project used IBM Granite LLM. Version of LLM that used in this project is IBM Granite 3.3 8b instruct. Using AI in this project help to finding and identifying problem statements that stated above. AI can be used to analyze, visualize and finding the key points that appear on the dataset that could become the answer that can answers all problem statement. 

## References
- Luckin, R., Holmes, W., Griffiths, M., & Forcier, L. B. (2016). Intelligence Unleashed: An Argument for AI in Education. Pearson Education.
- IBM (2024). IBM Granite Code & Instruction Models. Retrieved from https://huggingface.co/ibm-granite/granite-3.3-8b-instruct
