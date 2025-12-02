# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
# Name : HARIPRASATH S
# RegNo : 212222240034

## AIM
To evaluate and compare the effectiveness of different prompting strategies (zero-shot, few-shot, chain-of-thought, and role-based) on multiple AI platforms (ChatGPT, Gemini, Claude, Copilot) for summarizing a 500-word article about “Introduction to Artificial Intelligence”.
This helps understand how prompt design influences summary quality across platforms.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience


---

## **Algorithm**

1. **Article Selection**
Select a ~500-word article titled:

## Introduction to Artificial Intelligencey:

Artificial Intelligence (AI) is the simulation of human intelligence in machines that are programmed to think, learn, and act. The concept of AI originated in the 1950s, and since then it has grown into a major technological field. AI systems are capable of performing tasks that typically require human intelligence, such as recognizing speech, making decisions, identifying patterns, and solving problems.

What is AI?

AI refers to systems that can analyze information, learn from data, and make decisions. AI can be classified into two categories: Narrow AI, which performs a specific task (like voice assistants), and General AI, which would perform any intellectual task a human can. Most current AI systems fall under Narrow AI. Key components of AI include data, algorithms, and computing power.

How AI Works?

AI systems follow several steps:

Data Collection – The system gathers relevant data from various sources (text, images, speech, sensors).

Training – Algorithms learn from patterns in the data.

Inference – The trained model uses its knowledge to make predictions.

Feedback Loop – The model refines itself based on errors.

Modern AI often uses Machine Learning (ML) and Deep Learning (DL) to improve accuracy. Neural networks, inspired by the human brain, allow AI to process large datasets.

Key Features of Blockchain:

Automation – AI can automate repetitive tasks, increasing efficiency.

Accuracy – AI models can detect patterns humans may miss.

Adaptability – AI continuously improves through new data.

Applications of Blockchain:

AI is used in:

Healthcare – Disease prediction, medical imaging analysis.

Finance – Fraud detection, risk assessment.

Transportation – Self-driving cars and route optimization.

Education – Personalized learning tools.

Customer Service – Chatbots and virtual agents.

Conclusion:

Artificial Intelligence is changing how industries operate. With its ability to learn, adapt, and automate complex tasks, AI continues to expand into new domains. Understanding AI fundamentals helps students appreciate how it influences modern technology and the global economy.

3. **Prompting Strategies Definition**
  Same as your original experiment:

Zero-shot → Summarize directly without examples.

Few-shot → Provide 2–3 sample summaries first.

Chain-of-Thought → Explain reasoning steps before summarizing.

Role-based → Tell model to act as a professor or educator.


4. **Platform Selection**
   Use the following AI platforms:
ChatGPT

Gemini

Claude

Copilot


5. **Execution**
  For each platform:

Run all four prompt types

Generate summaries

Note response time

Record clarity and structure

6. **Evaluation Criteria**
   Evaluate:

Accuracy

Coherence

Simplicity

Speed

User Experience
7. **Scoring & Analysis**

   * Assign scores (1 to 5) for each criterion across all combinations.
   * Tabulate results for comparison.
   * Identify the best-performing strategy-platform combination.

---

## Bar chart:

<img width="1024" height="1024" alt="Gemini_Generated_Image_vmqkxwvmqkxwvmqk" src="https://github.com/user-attachments/assets/ce881a03-7ddf-4a64-8b51-ce83be6505e1" />
Platform	Prompt Type	Accuracy	Coherence	Simplicity	Speed	UX	Total (/25)


| Platform | Prompt Type      | Total Score |
|----------|-------------------|-------------|
| ChatGPT  | Zero-shot         | 22          |
| ChatGPT  | Few-shot          | 24          |
| ChatGPT  | Chain-of-Thought  | 22          |
| ChatGPT  | Role-based        | 24          |
| Gemini   | Zero-shot         | 19          |
| Gemini   | Few-shot          | 20          |
| Claude   | Chain-of-Thought  | 23          |
| Claude   | Role-based        | 24          |
| Copilot  | Zero-shot         | 18          |
| Copilot  | Few-shot          | 20          |


## **Result**

The experiment successfully applied four prompting strategies across four AI platforms to summarize a technical article on Artificial Intelligence. The comparison showed that prompt design significantly affects summary quality. ChatGPT performed best in detailed explanations, while Claude provided the most structured and educational summaries. Gemini and Copilot performed well in speed and ease of use.

---




