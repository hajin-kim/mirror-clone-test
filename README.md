# Test Git Mirror Clone

On GitHub via another account,

1. Create a repository.
2. Set your primary account as a collaborator.

On GitHub via your primary account,

1. Create a new empty repository.

On local with your primary account,

1. `git clone --mirror "$REPOSITORY_URL"`
2. `cd "$REPOSITORY"`
3. `git remote set-url --push origin "$NEW_REPOSITORY_URL"`
4. `git push --mirror`
