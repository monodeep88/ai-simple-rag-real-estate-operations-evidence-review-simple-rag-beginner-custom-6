# Generation Notes

Mode: ai

Model: groq / llama-3.1-8b-instant

Fallback reason: OpenAI limit reached. Automatically switched to Groq.

Architecture: Real Estate Policy Assistant

Template path: templates/simple-rag/real-estate-policy-assistant

Short description:

A beginner-friendly AI-powered RAG (Red, Amber, Green) system for real estate operations evidence review

Architecture notes:

- The system will use a microservices-based architecture to ensure scalability and maintainability.

Project planner agent workflow:

- Architecture Agent: Define app boundaries, data flow, runtime stack, and integration points. Outputs: The system will use a microservices-based architecture to ensure scalability and maintainability.
- Backend Agent: Design FastAPI modules, service contracts, validation, and error handling. Outputs: Evidence Review Service: Reviews evidence and returns a list of issues; RAG Categorization Service: Categorizes issues as Red, Amber, or Green; Compliance Checker Service: Checks compliance with regulations
- Frontend Agent: Design React screens, state flow, controls, and user feedback states. Outputs: Evidence Upload: Allows users to upload evidence; Issue List: Displays a list of issues; RAG Categorization: Displays the RAG categorization of issues
- Database Agent: Design persistence models, sample data, indexes, and audit records. Outputs: Run history; Source document metadata; Generated workflow audit records
- Testing Agent: Define contract tests, smoke tests, and generated project validation. Outputs: Unit testing and integration testing using Pytest
- DevOps Agent: Define environment variables, Docker workflow, and repository packaging. Outputs: Docker-ready project; Environment sample file; GitHub repository upload
- Reviewer Agent: Review the generated plan for completeness, security, and portfolio quality. Outputs: Evidence Upload: User uploads evidence; Issue Detection: System detects issues; RAG Categorization: System categorizes issues as Red, Amber, or Green
