# Topic 5 — Assessment Overview

## Objective

Integrate a clean Knowledge Guide into the AI Job Application Assistant and validate grounded, source-aware behavior.

## Implementation

The Custom GPT uses `AI_Job_Application_Assistant_Knowledge_Guide.md` as its reference source for documented application-support processes, standards, definitions, and rules. Instructions were updated with Knowledge priority, anti-hallucination, source-reference, unsupported-question, and misleading-premise rules.

## Validation Coverage

The six tests cover:

1. Fully covered knowledge — skill-match classifications.
2. Fully covered knowledge — fabricated metrics and achievements.
3. Fully covered knowledge — requirements outside the Knowledge Guide.
4. Partially covered knowledge — education section guidance.
5. Uncovered information — software-engineer salary data.
6. Misleading premise — universal ATS-score claim.

Final result: **6/6 PASS**.

## Key Challenge and Resolution

During the first run of the uncovered salary test, Web Search supplied external salary information. For the final assessment validation, Web Search was disabled so the GPT would identify the topic as outside the Knowledge Guide instead of supplying unsupported external data.

## Assumptions

The Knowledge Guide is authoritative for the assistant's documented process and definitions. For a specific application, the user's provided job description and resume are the source of truth for application-specific facts.

## Submission Resources

- Custom GPT: https://chatgpt.com/g/g-6ab32eeab8c88191915986ea8efad18d-ai-job-application-assistant
- Loom: https://www.loom.com/share/c146a88f091640bc932602bee5614938
- GitHub: https://github.com/shaikshahid777/ai-job-application-assistant-knowledge-integration
- Assessment PDF: `Topic_5_Knowledge_Integration_Assessment.pdf`
