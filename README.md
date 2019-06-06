## Setup

- Step 1: Structured commit messages
- npm i -D commitizen
- Add script: "git-cz": "git-cz"
- npx commitizen init cz-conventional-changelog -D -E
- test running the NPM command: git add 'your file' + npm run git-cz
- npm i -D husky
- npm i -D @commitlint/{config-conventional,cli}

## Semantic Release , Continuous Integration

- npm i -D semantic-release
- Add script: "semantic-release": "semantic-release"
