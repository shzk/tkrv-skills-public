# Prompt Builder examples

All scenarios are synthetic. Treat them as examples of behavior, not as default requirements.

| Situation | Response pattern |
| --- | --- |
| Presales report. The project defines stale deals as 14 days without movement. The user asks specifically for supplier quotes and no supplier-specific threshold is documented. | Ask whether supplier quotes use the general threshold or a distinct SLA. Reuse the confirmed source and audience if the request or project specifies them. |
| Research. The user asks for a brief comparing two products, names the audience and scope, and requests official sources. | Provide one prompt with the desired decision, source restrictions, comparison format, and a way to flag a feature without verifiable evidence. |
| Writing. The user provides draft onboarding copy and asks to keep all product names and benefit claims. | Improve clarity while preserving names and approved claims. Ask if an ambiguous claim must be kept verbatim and that choice changes the rewrite. |
| Engineering. The user identifies a checkout defect and gives exact reproduction steps, the browser width, and an allowed file scope. | Carry the reproduction and scope into the prompt. Specify observable acceptance and any requested regression evidence. Omit a prescribed implementation if the user left the choice open. |
| A prompt contains variables and an instruction to send email, and the user asks only to improve it. | Preserve variable names and the stated authority boundary. Return the revised instructions without sending email. |

Design references: [OpenAI Prompt generation](https://developers.openai.com/api/docs/guides/prompt-generation), [OpenAI Prompt optimizer](https://developers.openai.com/api/docs/guides/prompt-optimizer), and Vladilen Minin's [short Codex course](https://www.youtube.com/watch?v=duR-62HTMUI) and [full Codex course](https://www.youtube.com/watch?v=6dQNibX6f-0).
