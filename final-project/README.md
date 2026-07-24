# Final Project — EchoLeak (CVE-2025-32711)

[⬅ Back to main README](../README.md)

**Format:** 20-slide video presentation

This presentation analyzes **EchoLeak (CVE-2025-32711)**, the first publicly documented zero-click prompt injection vulnerability affecting Microsoft 365 Copilot.

📺 **Video:** [Watch on YouTube](https://www.youtube.com/watch?v=8dpNJy1rJ9A)

## 📚 Topics Covered
- Microsoft 365 Copilot architecture
- Retrieval-Augmented Generation (RAG)
- Prompt injection attack flow
- Security impact
- OWASP Top 10 for LLM Applications
- Mitigation recommendations

## 📝 Overview

EchoLeak demonstrated that an attacker could exfiltrate sensitive data from a Microsoft 365 Copilot session without any user interaction, by embedding malicious instructions inside content that Copilot's RAG pipeline would later retrieve and process as if it were trusted input. This made it a landmark case study in LLM-application security, since it showed how traditional web security boundaries (same-origin policy, permission scopes) do not automatically protect against injected natural-language instructions once they enter a model's context.

## ✅ Status
Project complete!
