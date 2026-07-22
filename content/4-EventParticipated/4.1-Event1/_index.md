---
title: "Event 1"
date: 2026-07-07
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---


# Report: “AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY”

### Event Purpose

-   To provide updates on the latest trends in Cloud Computing and the application of Generative AI (GenAI) in enterprise environments.
-   To share practical experience in designing cloud architectures, developing Multi-Agent AI systems, and enhancing cloud infrastructure security.
-   To create opportunities for the IT community to connect, exchange knowledge, and gain insights into the skills required for engineers in the rapidly evolving AI era.


### Speaker List

-   **Nguyễn Gia Hưng** - Solutions Architect, AWS Vietnam (Founder FCAJ)
-   **Tinh Truong** - Platform Engineer, GoTymeX
-   **Anh Pham** - Cloud Consultant, G-AsiaPacific Vietnam
-   **Thinh Nguyen** - DevOps Engineer, FCAJ
-   **Uyển Lê, Thảo Nguyễn, Mai Nguyễn** - GenAI Engineers, VIB
-   **Duc Dao** - Solutions Architect, Cloud Kinetics
-   **Vy Lâm** - Senior Business Systems Analyst, VPBank


### Key Highlights

#### Career Trends in the AI Era:
The rapid advancement of AI has significantly reduced the time and cost required to develop software, leading to an increasing demand for new digital products. As a result, IT engineers are expected not only to possess strong technical expertise but also to understand business requirements and demonstrate their capabilities through real-world projects.
#### Context Management for AI Applications:
One of the most important factors influencing the quality of AI-generated responses is context. Instead of supplying excessive information from multiple sources, only relevant and carefully selected data should be provided to minimize hallucinations and improve response accuracy.
#### Using Amazon Q for Workflow Automation:
The session demonstrated how Amazon Q can function as an AI Agent to automate tasks such as processing Excel data, generating visual reports, summarizing meeting discussions, and integrating with workplace tools through the Model Context Protocol (MCP).
#### Security Solutions with Amazon CloudFront:
The speaker explained how Amazon CloudFront efficiently distributes web traffic while utilizing Flat-rate Pricing to reduce unexpected costs. In addition, VPC Origin enables secure connections to backend services located within private subnets, minimizing direct exposure to the public Internet.
#### Building GenAI Products During a Hackathon:
The presenters shared their experience developing a serverless AI-powered user interface generation platform using multiple AI Agents. Rather than regenerating the entire interface after every modification, they implemented partial component editing, significantly reducing AI resource consumption and improving development efficiency.
#### Ensuring LLM Reliability:
The session discussed why Large Language Models (LLMs) may still produce different outputs even when the temperature is set to zero due to inference processes and hardware variations. To improve consistency, several techniques were recommended, including JSON Mode, self-hosted models, and systems capable of validating and handling abnormal responses.
#### Designing Enterprise-Grade Multi-Agent Systems:
The final presentation introduced an enterprise Multi-Agent architecture where specialized AI Agents collaborate throughout the business credit evaluation process. It also emphasized critical security considerations, including Prompt Injection prevention, Audit Trail implementation, API key management, and risk mitigation for MCP-based systems.


### What Was Learned

- **Practical Product Development Mindset:** 
I learned that successful software products should be built around business problems and user needs rather than focusing solely on technology. Dividing responsibilities among specialized AI Agents also improves system scalability, maintainability, and overall efficiency.

- **Cloud Architecture and Security:** 
I gained a better understanding of how Amazon CloudFront and VPC Origin can be combined to secure backend services, prevent direct Internet access, and strengthen application security.

- **AI Risk Management:** 
I realized that AI models can still generate inaccurate or improperly formatted outputs. Therefore, production systems should always include validation mechanisms, error handling, and fallback strategies instead of relying entirely on AI-generated results.


### Work Application

-   Implementing a Multi-Agent Architecture: Assign individual AI Agents to handle user preference analysis, recipe recommendations, and nutritional calculations, thereby improving system accuracy.
-   Optimizing Content Generation: Update only the modified components instead of regenerating the entire output, reducing both processing time and AI usage costs.
-   Configuring Appropriate AI Parameters: Use a low temperature together with JSON Mode to generate structured and consistent outputs that are easier to process.
-   Strengthening Security: Deploy CloudFront together with VPC Origin while providing only necessary context in prompts to reduce the risks of Prompt Injection and unnecessary data exposure. 


### Event Experience

The **“AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY”** provided me with valuable practical experience and new perspectives on integrating AWS Cloud with Generative AI in modern software development. Through the presentations, I gained a deeper understanding of how to build AI systems that are not only efficient but also reliable and secure for enterprise deployment.

#### Learning from High-Expertise Speakers

-   Speakers from AWS, VIB, GoTymeX, and Cloud Kinetics shared valuable real-world experiences in designing, deploying, and operating large-scale technology systems.
-   Practical case studies, including Hackathon projects and enterprise credit evaluation systems, helped me better understand how Multi-Agent architectures can solve complex business workflows.


#### Hands-on Technical Insights

-   I gained deeper insights into how Large Language Models work, the causes of hallucinations, and the impact of Temperature and JSON Mode on output quality.
-   The sessions on Amazon CloudFront and VPC Origin helped me better understand secure cloud infrastructure design, DDoS protection, and cost optimization for high-traffic applications.
-   I was also introduced to the Model Context Protocol (MCP), Prompt Injection attacks, and MCP-related security risks, giving me a clearer understanding of the challenges involved in integrating AI into enterprise systems.

#### Lessons Learned
-   Splitting a system into specialized AI Agents improves scalability, processing efficiency, and long-term maintainability.
-   AI should always be treated as an assistant rather than a fully autonomous decision-maker. Real-world applications must include validation and recovery mechanisms for inaccurate or improperly formatted outputs.
-   Security should always be a top priority in GenAI applications. Protecting infrastructure with CloudFront and VPC Origin, together with proper API key management and rotation, is essential for maintaining system security.

#### Event Photos
* Add your event photos here

![Event 1](/images/4-EventParticipated/image1.png)
![Event 1](/images/4-EventParticipated/image2.png)