# Contributing to SearchIT

Thanks for your interest in improving SearchIT! This is a small, dependency-free static app, so contributing is easy.

## Getting Started

1. Fork and clone the repository.
2. Open `index.html` directly in your browser — no build step or server required.
3. Make your changes and refresh the browser to see them live.

## Guidelines

- **Keep it dependency-free.** The project intentionally has no build tools, frameworks, or package manager. Please avoid introducing new external dependencies unless there's a strong reason.
- **Keep it a single file (or minimal set of files).** The app is designed to be simple to host and share. If you add assets, keep them small and well-organized.
- **Match the existing style.** Use the existing color palette (`--ink`, `--gold`, `--parchment`, etc.), fonts (Playfair Display, Inter, Lora), and layout conventions already defined in the `<style>` block.
- **Test all states.** When changing search behavior, verify the idle, loading, error, and result states all still work correctly.
- **Respect the Wikipedia API.** Don't add excessive or unnecessary requests; this app relies on Wikipedia's free public API and should use it responsibly.

## Reporting Issues

If you find a bug or have a feature idea, please open an issue describing:
- What you expected to happen
- What actually happened
- Steps to reproduce (if applicable)
- Browser/OS, if relevant

## Pull Requests

- Keep PRs focused on a single change or fix.
- Describe what you changed and why in the PR description.
- Test your changes in a browser before submitting.

## Code of Conduct

Be respectful and constructive. This is a small community project — kindness goes a long way.
