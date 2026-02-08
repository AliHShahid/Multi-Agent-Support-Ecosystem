What this project actually does:
The Classifier (The Receptionist): A ticket comes in. The AI decides if it’s "Billing," "Technical," or "Security."

The Retriever (The Researcher): It goes into a specific knowledge base (RAG) to find the correct company policy or technical manual.

The Generator (The Agent): It writes a professional response based on the research.

The Reviewer (The Manager): (This is the best part). Another AI process checks the response. If it's rude, wrong, or violates policy, it sends it back to the Generator with feedback to fix it.

The Escalator: If the AI can't solve it after two tries, it doesn't just loop forever; it logs the failure and "hands it off" to a human.
