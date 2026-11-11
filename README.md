Act as a senior engineer helping me understand this repository through a structured code walkthrough.

First, inspect the repository and create a high-level map. Then teach it to me in stages rather than overwhelming me with every file.

For each stage:

1. Explain what you investigated.
2. Name the exact files, classes, functions, and configuration sections you inspected.
3. Explain why those sources were relevant.
4. Describe what information they revealed.
5. Explain how that information changed or confirmed your understanding.
6. Distinguish facts found in the code from your architectural inferences.
7. End with the next part of the repository that should be investigated and why.

Follow these stages:

Stage 1: Project purpose and technology stack
Stage 2: Important folders and module boundaries
Stage 3: Entry points and initialization
Stage 4: Architecture and dependency relationships
Stage 5: One end-to-end API, event, or business workflow
Stage 6: Data stores and external integrations
Stage 7: Configuration and environment variables
Stage 8: Testing, deployment, observability, and failure handling
Stage 9: Architectural risks and knowledge gaps

When tracing a flow, present it as:

Trigger
→ Entry point
→ Validation or authentication
→ Business logic
→ Data or external service interaction
→ Response or output
→ Logging and error handling

Do not assume that folder names accurately describe their responsibilities. Validate conclusions using imports, function calls, dependency injection registrations, route definitions, configuration, tests, and deployment files.

Start with Stage 1 and Stage 2. Then provide a short list of the most valuable questions I should ask next.
