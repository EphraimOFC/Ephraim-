# Security notes

- Configure `GEMINI_API_KEY` through the hosting provider's private environment settings.
- Never commit real API keys, session credentials, or tokens.
- This change removes the key from the AI plugin source; any previously committed key must be revoked/rotated by the key owner because removing it from current code does not erase Git history.
- Do not enable AI plugin requests unless the key is configured.
