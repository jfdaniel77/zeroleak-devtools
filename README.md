# ZeroLeak DevTools

**ZeroLeak DevTools** is a fully offline browser-based developer toolbox for working with sensitive tokens, payloads, credentials, and text transforms.

It is designed for security-conscious developers who need a fast, local alternative to web-based inspector tools. The app runs entirely from `index.html`/`zeroleak-devtools.html`, with no backend, no network traffic, and no persistent storage.

## Repository name suggestion

- `zeroleak-devtools`

## Repository description suggestion

Offline browser developer toolbox for sensitive auth, payload, and format tools. No network, no storage, no telemetry.

## Why this exists

Developers often need to inspect, transform, or validate sensitive data such as JWTs, JSON, YAML, GraphQL, and auth headers. Many existing tools are web-based and can raise privacy concerns.

ZeroLeak DevTools solves that by giving you a local, privacy-first environment with tools that run completely in the browser.

## Features

- Offline-only, privacy-first design
- Zero network requests
- No local storage of user input
- Input auto-clear sensitive mode
- Dark and light theme toggle
- Copy output to clipboard
- Base64 encode/decode
- HTTP Basic Auth header generator
- JSON Validator & Linter
- UUID Generator
- Timestamp Converter
- JWT Decoder and expiry status
- URL Encode / Decode
- YAML Linter
- XML Formatter / Validator
- Text Diff Viewer
- GraphQL Validator & Linter
- Cron Expression Parser
- Regex Tester

## Tech stack

- HTML
- CSS
- Vanilla JavaScript
- Single-file static app

## Security guarantees

- Runs locally in the browser
- No network calls
- No hidden telemetry
- No local storage of any user input
- All processing happens in-memory only

## How to run

1. Clone the repository
2. Open `zeroleak-devtools.html` in any modern browser

No build step required.

## Limitations

- No backend or server support
- No schema-aware GraphQL validation
- Linting is heuristic-based and not a full parser for every edge case
- Intended for developer convenience, not production security scanning

## Contribution guide

Contributions are welcome! If you want to help improve this project:

1. Fork the repository
2. Create a branch for your feature or fix
3. Keep changes small and focused
4. Open a pull request with a clear description

### Suggested contribution areas

- Add more offline tools
- Improve linting quality for JSON / GraphQL
- Enhance accessibility and mobile responsiveness
- Add unit tests and documentation

## License

This project is released under the MIT License.