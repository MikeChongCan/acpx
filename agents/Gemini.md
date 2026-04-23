# Gemini

- Built-in name: `gemini`
- Default command: `gemini --acp`
- Upstream: https://github.com/google/gemini-cli
- ACP startup honors the normal `acpx --timeout <seconds>` budget by default.
- `ACPX_GEMINI_ACP_STARTUP_TIMEOUT_MS` overrides the Gemini ACP initialize timeout when you need a Gemini-specific cap.
- `GEMINI_API_KEY` or `GOOGLE_API_KEY` can be used for headless auth, but existing Gemini login state may also work.
