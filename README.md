<div align="center">

![Image](https://github.com/user-attachments/assets/8ed826be-b50a-41fb-bd3d-fdb0654019b5)

# 🛒 Intelligent Multimodal Chatbot for Online Grocery Shopping

</div>

## Overview 🌐

The landscape of online grocery shopping is fraught with challenges such as navigating static interfaces, cumbersome product searches, and verifying product availability. Additional hurdles include varying levels of digital literacy, diverse language preferences, and physical constraints, which further complicate the shopping experience.

## Solution 🤖

To address these challenges, we have developed an intelligent, multimodal chatbot that seamlessly integrates with a retailer’s live inventory system. This innovative solution allows customers to place orders using natural voice, text, or image inputs, providing a dynamic and intuitive shopping experience.

### Key Features
- **Advanced Natural Language Understanding (NLU):** Intelligently interprets ambiguous inputs, prompting users for clarification when necessary.
- **Error Correction:** Adapts to real-world user behavior, leveraging cognitive capabilities of large language models (LLMs) like OpenAI's GPT-4 and GPT-4o.
- **Order Tracking and Post-Sale Services:** Ensures comprehensive user experience with efficient handling of product discovery, inventory validation, and guided ordering in real time.

## Technology and Tools 🛠️

- **Semantic Kernel:** Enhances the chatbot's ability to interpret and respond accurately by processing semantic context.
- **OpenAI GPT-4 and GPT-4o Models:** Enable human-like responses, improving interaction quality and user satisfaction.
- **Azure AI Search:** Optimizes product search capabilities, ensuring relevant and accurate search results.
- **SQL Database:** Manages data integration with the retailer's inventory system, maintaining up-to-date product availability information.
- **Chain Lit:** Framework for frontend development, providing a user-friendly interface supporting multimodal interactions.
- **Literal API:** Ensures chat data persistence, securely storing user interactions for future reference or analysis.

## Value Proposition 🎯

Our chatbot revolutionizes the digital grocery shopping experience by adapting to each customer's preferred mode of interaction. It enhances accessibility, saves time, reduces dropout rates, and improves customer satisfaction (CSAT).

## Impact 📈

1. **Reduces Operational Friction:** Streamlines the shopping process, reducing barriers and delays.
2. **Improves Order Conversion Rate:** Facilitates a smoother shopping experience, leading to higher sales conversion.
3. **Enhances Customer Satisfaction (CSAT):** Delivers a user-friendly experience that meets diverse customer needs.
4. **Increases Customer Loyalty:** Provides a personalized and efficient shopping experience that encourages repeat visits.
5. **Offers Scalability:** Designed to handle increased user interactions and expand as the business grows.

---

In summary, this intelligent chatbot not only addresses the existing challenges in online grocery shopping but also sets a new standard for customer interaction and service in the digital retail space.




<div align="center">

# 🧠 Semantic Kernel Multi-Agent Architecture
![Image](https://github.com/user-attachments/assets/d94f9704-0c63-41c2-9fb8-5649227a40bb)

</div>

## Overview 📊

This architecture represents a Semantic Kernel Multi-Agent system, integrating various components and services to enhance user interaction and processing capabilities. It leverages advanced technologies to create a robust, adaptive system for superior user experiences.
It has been designed to harness the power of advanced AI services and development tools, ensuring seamless interactions across multiple channels. With provisions for human oversight and comprehensive monitoring, it offers a responsive, resilient, and adaptable system that meets evolving user needs and technological advancements.

<div align="center">

# Prompt Flow
![Image](https://github.com/user-attachments/assets/ad11d46d-0bfe-44d9-be0b-76b1e0bc43a6)
</div>

## Agent Descriptions 🧩

This diagram illustrates the interactions between the different agents within the system. Each agent has a specific role and set of functionalities designed to enhance the user's experience:

1. **Router Agent (GROOT) 🌐:**
   - **Role:** Directs inquiries to the appropriate specialist agent.
   - **Functionality:** Analyzes queries for keywords related to product information, billing, or orders.

2. **Product Agent 📦:**
   - **Role:** Provides detailed product information.
   - **Functionality:** Uses the ProductSearch Plugin to verify and deliver accurate product details.

3. **Order Agent 🛒:**
   - **Role:** Processes product-related requests and generates invoices.
   - **Functionality:** Identifies product details, verifies information, calculates totals, and formats invoices.

4. **Query Agent 🔍:**
   - **Role:** Manages SQL database interactions.
   - **Functionality:** Inserts invoice data and checks for duplicates.

5. **Invoice Agent 🧾:**
   - **Role:** Retrieves previous order invoice details.
   - **Functionality:** Provides users with past invoice information upon request.

---


