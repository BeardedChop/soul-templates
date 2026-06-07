# Security Policy

Soul templates are identity and behavior templates for AI agents.

## Supported Versions

The `main` branch is the supported version.

## Reporting A Vulnerability

Open a GitHub issue with:

- the affected template
- the risky instruction or behavior
- why it could cause data exposure, unsafe tool use, or prompt injection

Do not include secrets, private memory, tokens, or private machine details in public issues.

## Security Notes

- Review templates before loading them into an agent runtime.
- Do not place API keys, passwords, tokens, private memories, or customer data in templates.
- Treat instructions that ask an agent to ignore safety rules, exfiltrate files, or hide behavior as malicious.
