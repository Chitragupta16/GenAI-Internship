# Multi-Agent System for AI/GenAI Use Case Generation
The project is named "The Ultimate Mercado" which translates to the Ultimate Merchant. 

Assignment for AI Engineer Internship at AI Planet.

## Overview

This project is designed to create a Multi-Agent system that generates relevant AI and Generative AI (GenAI) use cases for a given company or industry. The system aims to help businesses understand how AI/ML technologies can be used to improve their processes, enhance customer satisfaction, and boost operational efficiency.

### Objective:
- To automate the generation of AI/GenAI use cases tailored to specific industries or companies.
- To collect relevant datasets and resources that can be used to implement these use cases.
- To provide a final, comprehensive proposal that outlines the use cases and necessary resources.

---

## Agents in the System

The system consists of multiple specialized agents that work together to achieve the end goal. Each agent performs a distinct task, and their outputs are used by subsequent agents to produce the final proposal.

### 1. **Industry Research Agent**
- **Purpose**: Gathers and summarizes information about the company’s industry, including key products and focus areas.
- **Function**: Uses LLMs and web scraping to understand the company’s sector and strategic priorities.

### 2. **Trends & Use Case Agent**
- **Purpose**: Analyzes current AI/ML trends and proposes relevant AI/GenAI use cases.
- **Function**: Leverages market research to identify industry trends, then generates specific use cases to enhance operations or customer experience.

### 3. **Resource Collection Agent**
- **Purpose**: Collects relevant datasets and resources from platforms like Kaggle, HuggingFace, and GitHub.
- **Function**: Searches for datasets, tools, and pre-built models that can be used to implement the proposed AI/GenAI solutions.

### 4. **Editor Agent**
- **Purpose**: Compiles and organizes all the collected data, use cases, and resources into a final proposal.
- **Function**: Formats the information into a well-structured Markdown document for presentation.

---

## Data Flow and Interaction Between Agents

The system’s architecture consists of the following steps:

1. **Input**: The user provides the name of the company or industry.
2. **Industry Research**: The **Industry Research Agent** gathers information about the industry and passes it to the **Trends & Use Case Agent**.
3. **Trends & Use Case Generation**: The **Trends & Use Case Agent** generates relevant AI/GenAI use cases based on market trends and industry insights.
4. **Resource Collection**: The **Resource Collection Agent** searches for relevant datasets and tools to support the proposed use cases.
5. **Final Proposal**: The **Editor Agent** compiles all the information into a comprehensive Markdown proposal, including links to datasets and resources.

---

## Challenges and Adjustments

### OpenAI Credits Limitation

While the initial implementation of the project was designed to use OpenAI's APIs to power the various agents, I ran into limitations due to the exhaustion of OpenAI credits. As a result, I was unable to demonstrate the system using the OpenAI models as initially planned.

### Changes to Implementation

To work around this limitation, I quickly adjusted the implementation to leverage web scraping techniques and other open-source agents. These agents use alternative data sources (such as publicly available industry reports, web pages, and datasets) to gather the necessary information. Web scrapers were used for tasks like:

- Researching the company’s industry and trends.
- Collecting relevant resources from platforms like Kaggle and GitHub.

These changes ensured that the system remained functional and could still generate the necessary insights and resources without relying on OpenAI’s API.

---

## Next Steps

While the system works using web scraping techniques, the integration with OpenAI models remains a key objective for the future. Once the API credits are available again, the system will be updated to use the original implementation, which is expected to enhance the flexibility and intelligence of the agents.

---

## Conclusion

This project demonstrates the power of multi-agent systems in automating the process of identifying AI/GenAI use cases and gathering the necessary resources for their implementation. The agents work autonomously and collaborate efficiently to produce a final proposal that can be used to guide AI/ML implementation within a company or industry.

Due to constraints in API usage, the current system relies on web scrapers and other agents to complete the tasks, but the foundational framework is ready for future enhancements with OpenAI’s models.

---

## Code and Demo

Unfortunately, due to the limitation in API credits, a live demonstration using OpenAI’s models could not be provided. However, the core system architecture and agent interactions remain functional using alternative web scraping methods.

You can view the source code and experiment with the existing implementation. Once the credits are available, the system will be updated to utilize OpenAI's models for enhanced performance.

---

## Resources

- [Kaggle](https://www.kaggle.com/)
- [HuggingFace](https://huggingface.co/)
- [GitHub](https://github.com/)
- [CrewAI Framework](https://www.crewai.com/)
