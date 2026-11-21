# followyourwill-site
Follow Your Will — agency website

## How a change goes live

GitHub Pages serves the `main` branch of this repository to followyourwill.com. A commit on `main` is a live change, with no step in between. That includes anything under `/preview/`, which is public at followyourwill.com/preview/.

So the rule for this site is one change, one branch, one pull request:

1. Work happens on its own branch, never on `main`.
2. Each change opens as a draft pull request with a short before and after, and the files it touches.
3. Merging the pull request into `main` is the go-live. Only Will merges.
4. One pull request changes one thing, so a bad change can be reverted alone.
5. A revert is also a pull request, so the record shows what came back and why.

Nothing on a branch or in an open pull request reaches the live site.
