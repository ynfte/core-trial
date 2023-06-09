# YNFTE Core

The core of a project is the central, essential component that supports the rest of the system.

## Commit

See how a minor change to your commit message style can make you a better programmer.

### Commit rules

```
1. create a new branch with the name of the feature
2. rebase the development branch to new branch commit
3. merge the branch to development first for code review.

notes: only push the fast forward merge
```

### Commit format

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

### Commit example

```
feat: new model user in user module 
^--^  ^---------------------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

References:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
