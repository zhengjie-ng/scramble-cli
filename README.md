Welcome to your mini‑sprint! In the next 2 hours your squad of 3–4 developers will turn this scaffold into a working, test‑driven word‑scramble game you can play in the terminal.

## Learning goals

1. Git & GitHub  – clone, branch, commit, open a PR, review & merge.

2. JavaScript & Jest  – implement functions & make the tests pass, then extend with your own tests.

3. SCRUM teamwork  – pick a Scrum Master (SM), Product Owner (PO) & Devs; time‑box tasks, run a mini‑retro.

## Quick-start

```bash
# 1. Fork and clone the repo
$ git clone <your‑repo‑url> .
$ cd scramble-cli

# 2. Install dependencies
$ npm install

# 3. Run the tests – they should FAIL at first
$ npm test

# 4. Create a branch and start coding!
$ git checkout -b feat/implement-isCorrect

# 5. When all tests pass, open a Pull Request & get it reviewed
```

## Role suggestion

| Role                             | Primary focus                                                                                                              |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Scrum Master & Product Owner** | Clarify acceptance criteria, update backlog (/tasks.md). Keep the team on time (15‑min sprint planning, stand‑ups, retro). |
| **Dev A**                        | Implement `scrambleWord()` in `src/scramble.js`.                                                                           |
| **Dev B**                        | Implement `isCorrect()` & extend Jest tests.                                                                               |
| **Dev C**                        | Build CLI flow in `src/index.js` with Inquirer.                                                                            |
| **Dev D** (opt)                  | Add extras: score tracking, ASCII art, timer, etc.                                                                         |

## Project structure

```
📁 scramble-cli
├── README.md           ← what you are reading right now
├── package.json        ← npm scripts & deps
├── tasks.md            ← team backlog (add user stories!)
├── src
│   ├── index.js        ← CLI entry point (TODO)
│   └── scramble.js     ← game logic (TODO)
└── __tests__
    └── scramble.test.js← unit tests (some failing!)
```

## Sprint checklist

1. ✅ Clone repo
2. ✅ npm install
3. ✅ Branch off main
4. ✅ Write code & tests
5. ✅ PR & code review
6. ✅ Merge & celebrate! 🎉

## Extension ideas (if you finish early)

- Add colours with `chalk`.
- Persist high scores to a JSON file.
- Accept custom word lists from the command line (--words animals.txt).
- Git challenge: resolve a merge conflict deliberately created by two parallel branches.
