Architected and implemented the TypeScript REST API backend and other core services for the Qira product:

- The **complete pipeline** from user query to answer: Preprocessing, chat memory management, tool selection, tool execution, result formatting, retry loops and detailed error handling
- An entire suite of **LLM tools** that perform search (semantic, bm25, fuzzy, hybrid approaches) across multiple data sources, powering the core Qira answering system
- Integration of four API clients to fetch OE (Original Equipment) data
- An **automated evaluation system** to detect quality and performance regressions on commit and branch levels. Quality and performance improvements are tracked in live dashboards
- Extensive **observability platform** by tracing every step of the Qira system with OpenTelemetry, using semantic conventions to display results in Phoenix. This allows AHEAD to have a completely transparent look into the live operation of Qira, simplifying debugging and allowing cost estimations for token generations
- Azure, Ollama and HuggingFace embedding and LLM services for efficient semantic similarity search and text generation
- Making the app, infrastructure and CI/CD system **production ready** with maintainable structured logging, error handling and extensive unit/e2e testing systems based on Sentry, neverthrow and vitest
- Maintaining our **server infrastructure** with typical CI/CD workflows, automated unit/e2e tests, certificate renewals, backups and deployments on various stages using Docker and nginx for web hosting. 
- **Technical documentation** of all software components
- Some Angular frontend work
- Supporting product management by actively steering the product development
- Supporting a team of students with their project work
- Supporting team members in their day-to-day work to deliver maintainable and scalable solutions

