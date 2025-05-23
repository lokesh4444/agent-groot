<div align="center">

![Image](https://github.com/user-attachments/assets/8ed826be-b50a-41fb-bd3d-fdb0654019b5)

# 🛒 Intelligent Multimodal Chatbot for Online Grocery Shopping

</div>

## Overview 🌐

The landscape of online grocery shopping is fraught with challenges such as navigating static interfaces, cumbersome product searches, and verifying product availability. Additional hurdles include varying levels of digital literacy, diverse language preferences, and physical constraints, which further complicate the shopping experience.

## Solution 🤖

To address these challenges, we have developed an intelligent, multimodal chatbot that seamlessly integrates with a retailer’s live inventory system. This innovative solution allows customers to place orders using natural voice, text, or image inputs, providing a dynamic and intuitive shopping experience.

## Key Features 📋

<div align=center>
   
![Image](https://github.com/user-attachments/assets/4929472a-dec1-431c-8608-7cbcad92764c)

</div>

- **Advanced Natural Language Understanding (NLU):** Intelligently interprets ambiguous inputs, prompting users for clarification when necessary. Accepts both text and speech as inputs. Supports multiple languages.
- **Image Recognition and OCR:** Can identify products based on the image and search for that product. Can extract text from the image of a handwritten note to search for products.
- **Catalog Browsing:** Uses AI Search capabilities to search for the exact product or a similar product in the catalog.
- **Invoice Generation:** Can generate an invoice automatically in form of a PDF that can be downloaded.
- **Order Details Retrieval:** Generates dynamic SQL Queries to search for previous orders in the order database. 
- **Error Correction:** Adapts to real-world user behavior, leveraging cognitive capabilities of large language models (LLMs) like OpenAI's GPT-4 and GPT-4o.
- **Order Placing and Post-Sale Services:** Ensures comprehensive user experience with efficient handling of product discovery, inventory validation, and guided ordering in real time.

## Technology and Tools 🛠️

- **Semantic Kernel:** Enhances the chatbot's ability to interpret and respond accurately by processing semantic context.
- **OpenAI GPT-4, GPT-4o and Whisper Models:** Enable human-like responses, improving interaction quality and user satisfaction.
- **Azure AI Search:** Optimizes product search capabilities, ensuring renlevant and accurate search results.
- **MCP Server:** Utilizes a Model Context Protocol server to integrate .NET functions with Python code.
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


<div align="center">

# 🧠 Semantic Kernel Multi-Agent Architecture
![Image](https://github.com/user-attachments/assets/42c70c24-ee07-425f-81d5-0654cfe5c335)

</div>

## Overview 📊

This architecture represents a Semantic Kernel Multi-Agent system, integrating various components and services to enhance user interaction and processing capabilities. It leverages advanced technologies to create a robust, adaptive system for superior user experiences.
It has been designed to harness the power of advanced AI services and development tools, ensuring seamless interactions across multiple channels. With provisions for human oversight and comprehensive monitoring, it offers a responsive, resilient, and adaptable system that meets evolving user needs and technological advancements.


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
   - **Functionality:** Inserts invoice data and checks for duplicates.Also generates the pdf of the invoice using MCP functions

5. **Invoice Agent 🧾:**
   - **Role:** Retrieves previous order invoice details.
   - **Functionality:** Provides users with past invoice information upon request.

<div align="center">

![Image](https://github.com/user-attachments/assets/16750d75-7463-4553-a9f9-5a2e019a5ea1)
**Prompt Flow**
</div>

## Demo Video 🎥

<div align="center">

[![Alt text](https://img.youtube.com/vi/r6jJSbqAdy0/0.jpg)](https://www.youtube.com/watch?v=r6jJSbqAdy0)
</div>

## Code Repository 💻
   - https://github.com/eragornmitra/mm_retail_ai_chatbot_multi-modal
---
## Team Members 👥👥
- [Ishan Mukherjee](https://www.linkedin.com/in/ishan-mukherjee-385b1343?originalSubdomain=in)
- [Dhritiman Pal](https://www.linkedin.com/in/dhritimanpal?originalSubdomain=in)
- [Sarbo Mitra](https://www.linkedin.com/in/sarbo-mitra-50338a212?originalSubdomain=in)
- [Lokesh Das](https://www.linkedin.com/in/lokesh-chandra-das-670352193?originalSubdomain=in)

