# Commit Approach

## Introduction

These commit rules are designed to ensure consistency and clarity in our version control history. By following these guidelines, we can maintain a clean and understandable project history.
<div align="center">
  <img height="500" width='1000' src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXlveG5mOWE2YzluNHZndWJibmxsMjk3MHdnZ3AyNTFzNjJsaWt1OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MGdfeiKtEiEPS/giphy.webp"  />
</div>

## Commit Types

- **feat**: Commits that add a new feature
  - _Example:_ `git commit -m "feat(profile): add button for update call"`
- **fix**: Commits that fix a bug
  - _Example:_ `git commit -m "fix(login): correct authentication error"`
- **refactor**: Commits that restructure code without changing behavior
  - _Example:_ `git commit -m "refactor(database): optimize query performance"`
- **perf**: Commits that improve performance
  - _Example:_ `git commit -m "perf(api): reduce response time"`
- **style**: Commits that do not affect the meaning of the code (white space, formatting, etc.)
  - _Example:_ `git commit -m "style(css): format header styles"`
- **test**: Commits that add or correct tests
  - _Example:_ `git commit -m "test(api): add tests for user endpoint"`
- **docs**: Commits that affect documentation only
  - _Example:_ `git commit -m "docs(readme): update commit rules"`
- **build**: Commits that affect build components like build tools, CI pipeline, dependencies, etc.
  - _Example:_ `git commit -m "build(ci): add new deployment script"`
- **chore**: Miscellaneous commits (e.g., modifying .gitignore)
  - _Example:_ `git commit -m "chore(gitignore): add new patterns"`

<div align="center">
  <img height="500" width='1000' src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExcGhvYmpvYmp6aGo4ZWNzNGM2aTJld3Z3eWxjNjZkc2NtdGx3ZmVtNiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/SJ7jPehyWHp5ufoVzq/giphy.webp"  />
</div>

# Rules   ⬇️  :

### First Rule

Only one type per commit.

### Second Rule

The commit scope should be a noun describing a section of the codebase, surrounded by parentheses.

**Example:**

```bash
git commit -m "feat(profile): add button for update call"
```

### Third Rule

Link to Jira by writing the number of the task that was solved.

**Example:**

```bash
git commit -m "(JIRA-231) feat(dashboard): add sign-out button"
```

### Fourth Rule

Use `!` to draw attention to breaking changes.

**Example:**

```bash
git commit -m "feat!: send an email to the customer when a product is shipped"
```

### Fifth Rule

Write commit messages in the present tense, not past tense.

**Examples:**

```bash
git commit -m "refactor: change the text"  # Correct
git commit -m "refactor: changed the text" # Incorrect
```

<div align="center">
  <img height="500" width='1000' src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3Rocmx3eHp4cGFwd29zc3o3YndzaDZ2bmlzaTFtcTFvdTVya2hxcSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5eFRaqbiJjrL2A8SR7/giphy.webp"  />
</div>
