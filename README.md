# Experiment 4: Scenario-Based Report Using Diverse Prompting Techniques
**Name:** MARELLA DHARANESH
**Reg.No.:** 212222240062
## Lab Scenario: Smart Health Assistant System – MediGuide

---

## Introduction and Background

### 1. Introduction

With the growing demand for personalized healthcare among the elderly, smart digital assistants like MediGuide are becoming vital tools. MediGuide is specifically developed to aid seniors dealing with chronic illnesses such as diabetes, hypertension, and arthritis. Through natural language processing, it delivers tailored advice, medication reminders, and emotional support. By employing varied prompting strategies, MediGuide can offer more accurate, compassionate, and user-specific responses.
![image](https://github.com/user-attachments/assets/7b1b3396-8ac0-4d87-99f7-ff62c57f65a5)


### 2. Background

Managing chronic conditions is a constant challenge for older adults, who often struggle with medication schedules, lifestyle changes, and tracking health indicators. MediGuide addresses these concerns by providing:
- Customized health suggestions  
- Timely medication alerts  
- Daily wellness tips  
- Mental and emotional support

- ![image](https://github.com/user-attachments/assets/31b62ec9-9368-46b7-a844-818c8cd767db)
  

The integration of diverse prompting approaches ensures that responses are not only informative but also emotionally aware and contextually relevant.

![image](https://github.com/user-attachments/assets/6e1ce51d-2d52-4164-92fd-aa9ddc25ee07)

---

## Objective

The aim of this experiment is to explore how various prompting methods—such as zero-shot, few-shot, chain-of-thought, role-based, and multi-modal—enhance MediGuide's response quality across real-world healthcare scenarios. Each technique is tested to assess its impact on clarity, personalization, and user engagement.

![image](https://github.com/user-attachments/assets/a8b0419f-38bc-4ecb-83db-88258d8fcad9)


---

## Prompting Techniques Applied

We employed the following strategies to fine-tune MediGuide's interaction capabilities:

- Zero-Shot Prompting: Using a single query without examples, relying on general AI understanding.
- Few-Shot Prompting: Providing sample conversations to guide response generation.
- Chain-of-Thought Prompting: Encouraging logical reasoning and step-by-step explanations.
- Role-Based Prompting: Assigning MediGuide a specific persona, such as a caring assistant.
- Multi-Modal Prompting: Combining visual data (e.g., images of pillboxes) with text input for enriched context.

![image](https://github.com/user-attachments/assets/ea50d7f2-5bbc-4f88-9653-a5ff2a87963a)

---

## Use Cases and Prompting Outcomes

### 1. Zero-Shot Prompting

**Scenario**: A user seeks natural ways to manage high blood pressure.

**Prompt**:  
What are some natural methods to lower high blood pressure?  

**Output**:
> To naturally control high blood pressure, consider reducing salt, eating more fruits and vegetables, staying active, managing stress, avoiding alcohol, and adhering to your prescribed treatments.

**Result**:  
Delivers a general yet helpful response. This method is quick but lacks contextual adaptation.

---

### 2. Few-Shot Prompting

**Scenario**: The user asks for dinner ideas suitable for diabetes.

**Prompt**:  
Example 1:  
User: What can I eat if I have diabetes?  
MediGuide: Foods high in fiber, lean proteins, and non-starchy vegetables are excellent choices. Limit sugary beverages.  

Example 2:  
User: What's a good diabetic breakfast?  
MediGuide: Oatmeal topped with berries and a handful of nuts is a nutritious start.  

New Input: What can I have for dinner?  

**Output**:
> MediGuide: A diabetic-friendly dinner might include grilled salmon, steamed vegetables, and a serving of quinoa.

**Result**:  
Context-aware response that builds on previous examples for improved relevance.

---

### 3. Chain-of-Thought Prompting

**Scenario**: The user wonders if they can stop medication after feeling better.

**Prompt**:  
If someone feels better while on blood pressure medication, should they stop? Explain step-by-step.  

**Output**:
> Feeling better doesn’t mean the condition is cured. Blood pressure medication manages symptoms, and stopping it without medical guidance can lead to serious issues. Always consult a healthcare provider before making changes.

**Result**:  
Encourages reasoning and emphasizes safety in health-related decisions.

---

### 4. Role-Based Prompting

**Scenario**: A user shares they are feeling emotionally low.

**Prompt**:  
You are a warm, empathetic health assistant. The user says, “I’ve been feeling lonely lately.”  

**Output**:
> I'm really sorry you're feeling this way. You’re not alone—I'm here for you. Would you like to chat or try a relaxation exercise together?

**Result**:  
Demonstrates empathy and emotional intelligence, ideal for mental health support.

---

### 5. Multi-Modal Prompting

**Scenario**: A user uploads a photo of their pillbox and asks if it’s organized correctly.

**Prompt**:  
(Image uploaded) Can you confirm if today’s medication is set correctly?  

**Output**:
> It appears your Monday morning medications are properly sorted, except for your diabetes tablet, which is missing. Please double-check your dosing schedule.

**Result**:  
Leverages visual input for more personalized, actionable guidance.

---

## Algorithm Workflow Overview

1. Input Received (Text/Image)  

2. Context Identification (Medical, Emotional, Routine)  

3. Prompt Strategy Selected (Based on Use Case)  

4. AI Response Generated  

5. User Feedback Tracked  

6. Continuous Response Refinement

![image](https://github.com/user-attachments/assets/5c43d979-4f6a-4fe8-b849-0e9a33244ea4)

---

## Conclusion

By leveraging diverse prompting techniques, MediGuide is able to:
- Offer medically accurate, context-aware recommendations  
- Provide mental and emotional support  
- Enhance medication compliance  
- Respond with empathy and intelligence  

As AI in healthcare evolves, using specialized prompting methods will be essential in designing assistants that are not only smart but also caring and accessible to older adults managing chronic illnesses.

---
