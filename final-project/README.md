# Final Project - EchoLeak (CVE-2025-32711)

[Back to main README](../README.md)

Format: 20-slide video presentation

This presentation analyzes EchoLeak (CVE-2025-32711), the first publicly documented zero-click prompt injection vulnerability affecting Microsoft 365 Copilot.

Video: [Watch on YouTube](https://www.youtube.com/watch?v=8dpNJy1rJ9A)

## Topics Covered

- Microsoft 365 Copilot architecture
- Retrieval-Augmented Generation (RAG)
- Prompt injection attack flow
- Security impact
- OWASP Top 10 for LLM Applications
- Mitigation recommendations

## Overview

EchoLeak demonstrated that an attacker could exfiltrate sensitive data from a Microsoft 365 Copilot session without any user interaction, by embedding malicious instructions inside content that Copilot's RAG pipeline would later retrieve and process as trusted input. Because the attack required no click, download, or explicit action from the victim, it highlighted a fundamental gap in how large language model applications distinguish between trusted system instructions and untrusted retrieved content.

The presentation walks through Copilot's architecture and how RAG integrates external data into a model's context, traces the exact injection and exfiltration flow used in the exploit, and maps the vulnerability against the OWASP Top 10 for LLM Applications. It concludes with concrete mitigation strategies, including stricter content provenance checks, output filtering, and architectural safeguards that separate instructions from retrieved data.

## Status

Project complete.
