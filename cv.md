# Marc Julian Schwarz

**Software Engineer - Data Scientist - AI Engineer**

I build production-ready, high-quality software that solves real user needs.

## Personal Information

info@marc-julian.de

## Web

https://marc-julian.com  
https://marc-julian.com/blog  
https://github.com/marcjulianschwarz  
https://linkedin.com/in/marcjulianschwarz  

## Professional Work

##### AI Engineer - GovRadar GmbH - 02/2026-Today
Munich, Germany (Remote)

First hire on the new AI agents team at GovRadar where I built the Python agent architecture for [GovBot](https://www.govradar.net/l%C3%B6sung) from scratch and took it to production, now used by 600+ public administrations across Germany.

- The **complete agent architecture** using PydanticAI, Azure OpenAI, FastAPI, Postgres, Redis and more:
    - Streaming agent events to the client via WebSocket connections
    - Integration of many internal microservices into the **tooling layer** for the agent
    - **Multi-agent** setups and **LLM** tools for complex outline generation, question answering, text section generation and conversation state such as user preferences
    - Handling **files** uploaded by users
    - **Hybrid search**, **RAG** and **reranking** in big data indices via **Elasticsearch** 
    - **Production-grade** code with a focus on maintainability, error handling, scalability, modularity and security
- A custom internal **evaluation framework** that is now used by multiple teams to keep track of quality and performance in LLM generation and search workflows
- Extensive **observability platform** including **tracing**, **event tracking**, **worker health dashboards** and **evaluation reports** that can be used by the entire team to monitor and debug our production systems
- **Technical documentation** of all systems
- Made initial **architecture decisions** that drive the product today
- Set code standards across the project and set up contribution guidelines to keep code quality high
- Onboarded a new team member and helped with the **hiring process** for multiple positions in the company through coding cases and technical interviews

##### Software Engineer / Data Scientist - AHEAD Automotive GmbH - 04/2024-01/2026
Hamburg, Germany

Architected and implemented most of the TypeScript backend and other services for the AHEAD web platform and AI agent [Qira](https://www.qira.net/).

- The **complete pipeline** from user query to answer: Preprocessing, chat memory management, tool selection, tool execution, result formatting, retry loops and detailed error handling
- An entire suite of **LLM tools** that perform search (semantic, bm25, fuzzy, hybrid approaches) across multiple data sources, powering the Qira answering system
- Integration of four API clients to fetch OE (Original Equipment) data
- An **automated evaluation system** to detect quality and performance regressions on commit and branch levels. Quality and performance improvements are tracked in live dashboards
- Extensive **observability platform** by tracing every step of the Qira system with OpenTelemetry, using semantic conventions to display results in Phoenix. This allows us to have a completely transparent look into the live operation of Qira, simplifying debugging and allowing cost estimations for token generations
- Azure, Ollama and HuggingFace embedding and LLM services for efficient semantic similarity search and text generation
- Making the app **production-ready** with maintainable structured logging, error handling and extensive unit/e2e testing systems based on Sentry, neverthrow and vitest
- Maintaining our **server infrastructure** with typical CI/CD workflows, automated unit/e2e tests and deployments on various stages using Docker and nginx for web hosting
- **Technical documentation** of all software components
- Support in product management by steering the product development with concrete proposals
- Some Angular & Tailwind frontend work


##### Data Scientist - DATEV eG - 09/2022-03/2024
Nuremberg, Germany

Implemented and evaluated data science-related proofs of concept in the AI Office team.

- Evaluation of a PII (Personally Identifiable Information) identification procedure based on a NER (Named Entity Recognition) Ensemble
- **Semantics-preserving anonymization** of PIIs with subsequent re-identification for use with LLMs
- **Process mining** on legal documents  
- Record linkage for legal documents  
- MIP (Mixed-Integer Program) optimization for optimal employee calendar assignments  
- Assistance in implementing a **RAG (Retrieval Augmented Generation) system** for an intelligent chatbot on guideline documents
- RAG on video transcripts with video citations
- Bachelor's thesis "Mainframe Meets AI - Improving Legacy Code Generation Through Fine-Tuning of Large Language Models"
- **Topic classification** of scientific texts in the Franconian Data Science League Hackathon  
- Presentation at an employee meeting on the topic of ChatGPT and AI for DATEV  
- Development of several Streamlit web applications for various proofs of concept and internal dashboards  
- Support in many other machine learning projects


##### Research Assistant - Fraunhofer IIS - 04/2021-09/2022
Nuremberg, Germany

Worked in the "Machine Learning and Validation" research group.

- Motion capture data analysis
- Preprocessing and evaluation of the measurement data obtained from a motion capture system 
- Conducted literature research in the area of IMU in-field calibration and **Approximate Nearest Neighbor Algorithm** benchmarking 
- Several data analysis and preprocessing tasks, resulting in processed data that I made accessible via a **Flask API** and an accompanying web application
- Custom Streamlit component using **TypeScript and React** to display the data in a use-case specific dashboard view


## Education

##### Bachelor of Science - Data Science - 2020-2024
Friedrich-Alexander-Universität Erlangen Nürnberg

- Bachelor's thesis "Mainframe Meets AI - Improving Legacy Code Generation Through Fine-Tuning of Large Language Models"
- Used a Kubernetes cluster with four H100 GPUs to fine-tune a large language model on instruction-formatted legacy mainframe code to improve code generation performance for several tasks

##### General University Entrance Qualification - 2012-2020
Gymnasium Stein

## Testimonials

> I had the pleasure to work with Marc, and I highly recommend him as a Software Engineer and Data Scientist. He is extremely reliable, grasps new topics quickly, and delivers clean, effective results. He is a talented professional who brings great value to every team.
> **Jakob Cuda** - Senior Product Manager at AHEAD Automotive


## Key Skills

- Full-stack web development
- TypeScript, JavaScript, Python, a bit of Go
- Common Python packages for data science, machine learning, deep learning, natural language processing, web scraping and web development work. To name a few: scikit-learn, PyTorch, pandas, NumPy, Flask, NLTK, spaCy and many more 
- Backend development with NestJS (TypeScript) and FastAPI (Python)
- Web development with React, Next.js, Vue, Angular or simple HTML/CSS/JS apps
- AI: LLM agents, multi-agent systems, RAG, hybrid search, LLM evaluation, PydanticAI, Elasticsearch
- Cloud and observability: Azure, OpenTelemetry, Phoenix, Sentry
- CI/CD workflows with GitHub Actions and Docker containerization
- Testing tools: pytest and vitest
- Databases: SQLite, Postgres, MongoDB, Redis and both the Weaviate and Qdrant vector databases
- Self-hosting of web apps on Hetzner servers with nginx

## Open Source Work

##### Projects
- [Obsidian for Raycast](https://www.raycast.com/marcjulian/obsidian) - Obsidian notes at your fingertips. With 180,000+ installs
- [mdsnip.com](https://mdsnip.com/) - Share short unique URLs for beautifully rendered markdown snippets
- [sammlung.app](https://sammlung.app/) - Turns online consumption into creation, made for knowledge workers
- [counter.marc-julian.com](https://counter.marc-julian.com/) - Count anything here, inspired by Alltagszähler
- [Desk Automation](https://github.com/marcjulianschwarz/ha-desk-automation) - ESP8266 Height-Adjustable Desk Control with Home Assistant and Raycast Integration
- [Go Blog](https://github.com/marcjulianschwarz/go-blog) - Fast static site blog generator running on a single folder of markdown files. Written in Go.
- [Interactive Brain MRI Scan Dashboard](https://github.com/marcjulianschwarz/mri-scan-dashboard) - Explore and analyze MRI scans of brains with machine learning and neural networks
- More on my [GitHub](https://github.com/marcjulianschwarz), plus private projects I am happy to talk about

##### Writing
- [marc-julian.com](https://marc-julian.com/) - About me, CV, projects, blog and tools I use
- [marc-julian.com/blog](https://marc-julian.com/blog) - My blog
- [the-brew-code.de](https://the-brew-code.de) - German wiki about hobby coffee brewing
- [notes.marc-julian.com](https://notes.marc-julian.com/) - Public notes about tech, coding, math, machine learning and much more
- [university.marc-julian.com](https://university.marc-julian.com/) - University notes

## Other

- Won "The Tensor Tournament" machine and deep learning hackathon at my university in 2023
- Hosting and development of several smaller websites as voluntary work
- [Photography](https://marc-julian.com/photography/) - Some of my shots

## Languages

- German (native)
- English (fluent)
