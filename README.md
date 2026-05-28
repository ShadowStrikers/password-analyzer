# Password Strength Analyzer

A privacy-preserving password auditing tool that combines 
rule-based heuristics with AI-generated security explanations.

## Live Demo
[Try it here](https://yourusername.github.io/password-analyzer)

## How it works
- Checks length, character variety, and common patterns locally in the browser
- Estimates crack time based on entropy calculation
- Sends only structural findings (never the raw password) to an AI for plain-English analysis

## Privacy design
Raw passwords never leave the browser or touch any external server.
Only anonymized findings are sent to the AI explanation API.

## Built with
HTML, CSS, JavaScript, Anthropic Claude API
