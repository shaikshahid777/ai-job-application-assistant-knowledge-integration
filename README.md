# AI Job Application Assistant — Knowledge Integration

Topic 5 — Knowledge Integration assessment for a Custom GPT.

## Project

The AI Job Application Assistant supports fresh graduates, college students, and entry-level job seekers with job-description analysis, resume tailoring, skill-gap identification, cover letters, application responses, and readiness checklists.

## Assessment Implementation

The Custom GPT was configured with an uploaded Knowledge Guide as the primary source for covered application-support processes, standards, definitions, and rules. The instructions include anti-hallucination, source-reference, unsupported-question, and misleading-premise handling rules.

## Validation

Six validation tests were completed across fully covered, partially covered, uncovered, and misleading questions. The final validation result was 6/6 PASS.

See `test_qa_results.md` for the documented validation results.

## Knowledge File

See `AI_Job_Application_Assistant_Knowledge_Guide.md` for the assessment knowledge source.

## Resources

- Custom GPT: https://chatgpt.com/g/g-6ab32eeab8c88191915986ea8efad18d-ai-job-application-assistant
- Loom demonstration: https://www.loom.com/share/c146a88f091640bc932602bee5614938
- Assessment PDF: Topic_5_Knowledge_Integration_Assessment.pdf (provided with LMS submission)

## Configuration Note

Web Search was disabled during final validation of the uncovered-question test to ensure unsupported salary data was not supplied from external sources.
