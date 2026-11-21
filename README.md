# Tris-Bound

These are my user-level instructions for Codex. They cover how I want Codex to handle instruction provenance, authorization, implementation tradeoffs, and verification.

- [AGENTS.md](AGENTS.md) is the main instruction file.
- [Semantic boundaries](archives/semantic-boundaries.md) covers untrusted content, authorization, and passing payloads across interpreters.
- [Implementation and verification](archives/implementation-and-verification.md) covers scope, known limitations, and when to stop verifying.

To use this setup with the default Codex home, merge the guidance in `AGENTS.md` into `~/.codex/AGENTS.md` and copy the two reference files into `~/.codex/archives/`. If you use a different Codex home, adjust the reference paths in your copy of `AGENTS.md`.
