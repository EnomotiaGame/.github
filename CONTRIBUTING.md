# Contributing to ENOMOTIA's open-source projects

Thank you for looking. Everything in this organisation came out of building ENOMOTIA, a strategy game for the browser and phones, and we publish it because others meet the same problems. Your bug reports, ideas and pull requests are welcome, and they make these projects better for the game too.

These rules apply to every repository in the organisation unless the repository says otherwise.

## Reporting a bug

Open an issue in the repository and include:

- what you did, with the smallest code that shows it;
- what you expected, and what happened instead;
- the versions involved (the project, the language, the database or platform).

A failing test is the best bug report there is.

## Suggesting a change

For anything larger than a small fix, open an issue first and describe the problem you want solved. We would rather agree on the shape of a change before you spend an evening on it. Small fixes (typos, docs, an obvious bug) can go straight to a pull request.

## Sending a pull request

- Keep it to one change. Two unrelated fixes are two pull requests.
- Add or update tests. Every project here is tested, and a change without a test is hard to accept.
- Run the project's checks before you push. For Go that is `gofmt`, `go vet ./...` and `go test -race ./...`. The README of each repository lists anything extra, such as a database.
- Don't add a dependency to a package that has none without discussing it first. Several projects promise a dependency-free core.
- Explain why in the description, not only what. The reason is what reviewers and future readers need.

## Security

Please don't report security problems in public issues. Use the repository's **Security** tab, then **Report a vulnerability**. The report reaches the maintainers privately, and we will work with you on a fix and a disclosure date.

## Licence

The projects are MIT licensed. By sending a contribution you agree that it is published under the same licence as the project.

## Conduct

Be kind and assume good faith. Criticise code, not people. We maintain these projects alongside a live game, so an answer may take a few days. Harassment and personal attacks are not tolerated, and the maintainers may remove comments or contributors that cross that line.
