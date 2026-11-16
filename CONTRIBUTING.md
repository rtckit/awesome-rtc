# Contribution Guidelines

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate;
- Suggested resources should bring out of box value to the audience:
  - Purely/overly commercial suggestions are not acceptable;
  - Literature from IETF, ITU and other similar bodies are likely too specialized to be accepted;
- Make an individual pull request for each suggestion;
- Use the following format: `- [PACKAGE](LINK) - DESCRIPTION.`;
- New categories, or improvements to the existing categorization are welcome;
- Keep descriptions short and simple, but descriptive;
- End all descriptions with a full stop/period;
- Check your spelling and grammar;
- Make sure your text editor is set to remove trailing whitespace.

GitHub Actions checks Awesome list formatting and links on pull requests and on
updates to `master`. You can run the same checks locally with Node.js 24 and
[lychee 0.24.2](https://github.com/lycheeverse/lychee/releases/tag/lychee-v0.24.2):

```sh
npx --yes awesome-lint@2.3.0 README.md
lychee --config .lychee.toml README.md CONTRIBUTING.md
```

Link-check exceptions are limited to the exact bot-blocked pages documented in
`.lychee.toml`. Please verify those pages manually when changing their entries.

Thank you for your suggestions!
