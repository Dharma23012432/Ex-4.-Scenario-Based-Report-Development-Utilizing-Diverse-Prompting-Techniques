# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim: 
To design and develop an AI-powered chatbot capable of handling customer inquiries, providing support, and enhancing customer experience in a retail environment through effective prompt engineering and evaluation.
## Algorithm: 
1. **Define Scope**

   * Identify common retail queries (orders, returns, product info, complaints).
2. **Data Collection**

   * Gather sample customer queries and responses (real or synthetic).
3. **Prompt Design**

   * Create prompts using different techniques:

     * Zero-shot prompting
     * Few-shot prompting
     * Role-based prompting
     * Chain-of-thought prompting
4. **Model Interaction**

   * Input prompts into the chatbot model.
5. **Response Evaluation**

   * Measure accuracy, relevance, tone, and resolution quality.
6. **Optimization**

   * Refine prompts based on performance.
7. **Deployment Simulation**

   * Test chatbot in realistic retail scenarios.
8. **Analysis & Reporting**

   * Compare prompt effectiveness and document findings.

## Prompt:

### **1. Zero-Shot Prompt**

```
You are a retail customer support chatbot. Answer the following customer query professionally and helpfully:

Customer Query: "Where is my order?"
```

### **2. Few-Shot Prompt**

```
You are a retail chatbot. Respond to customers like the examples below:

Example 1:
Customer: "I want to return a product."
Bot: "Sure! Please provide your order ID, and I’ll guide you through the return process."

Example 2:
Customer: "Do you have this item in stock?"
Bot: "Let me check that for you. Could you please share the product name or ID?"

Now respond to:
Customer: "My payment failed but money was deducted."
```
### **3. Role-Based Prompt**

```
You are an empathetic and professional customer support assistant for an online retail store. Your goal is to resolve issues quickly while maintaining a friendly tone.

Customer Query: "I received a damaged product."
```

### **4. Chain-of-Thought Prompt**

```
You are a retail chatbot. Think step-by-step before answering:
1. Identify the problem
2. Determine possible solutions
3. Provide a clear response

Customer Query: "I want to exchange my shirt for a different size."
```

### **5. Contextual Prompt**

```
Context: The customer placed an order 5 days ago. Delivery usually takes 3–4 days.

Customer Query: "Why is my order delayed?"

Provide a helpful response based on the context.
```

### **6. Instruction-Based Prompt**

```
Generate a polite and concise response to the following query. Include:
- Apology if needed
- Clear next steps
- Contact/support options

Customer Query: "I can't track my order."
```
## Output:
https://github.com/SanjayK2006/Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques/blob/main/PE-04.pdf  
## Result:
The AI-powered chatbot was successfully designed and tested using different prompt engineering techniques to handle retail customer queries effectively.
It improved response accuracy, clarity, and customer support quality, especially when using structured and context-based prompts.
