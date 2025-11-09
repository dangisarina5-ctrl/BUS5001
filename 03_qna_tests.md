## Prompt 2
**“Explain in simple terms what a Dialogflow CX Agent, Flow, and Page are, and how they interact.”**

### NotebookLM Answer (Summary)
- **Agent:** Acts as the virtual assistant that interprets user input and manages conversations.  
- **Flow:** Defines a conversation topic (e.g., ‘Coffee Order’). An agent can have multiple flows.  
- **Page:** Represents a single conversational state within a flow, where specific information is collected.  
- **Interaction:** Agent → contains Flows → made up of Pages; pages transition to move the dialogue forward.

### Evaluation
Matches lecture definitions exactly.  
Uses clear, student-friendly language.  
Excellent demonstration of NotebookLM’s ability to retrieve hierarchical relationships accurately.

---

## Prompt 3
**“List the steps required to build a basic chatbot in Dialogflow CX as described in this workshop document.”**

### NotebookLM Answer (Summary)
**Part 1 – Create Project**  
1. Open Dialogflow CX Console and log in.  
2. Create a new project and enable Dialogflow API.  
3. Create Agent, set region (Australia-southeast1), timezone GMT+10.  

**Part 2 – Build Breakfast Bot**  
1. Create “Coffee” Page.  
2. Set transition condition “true” → target page Coffee.  
3. Add agent response “Would you like some coffee?”  
4. Create “Yes” intent → transition to Breakfast Page.  
5. Create “No” intent → transition to End Flow.  
6. Add fulfilment on Breakfast page (“Would you like some breakfast?”).  
7. Test Agent.

### Evaluation
Step order fully matches the workshop.  
Minor omission: did not explicitly mention saving between steps.  
Excellent procedural clarity and structured reasoning.

