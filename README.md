# GIT Commit

This repository demonstrates the commit message style guide which is suggested by Udacity.  

## Message Structure

The layout of commit messages is shown as below. It consists of three distinct parts separated by a blank line. The title, an optional body and optional footer.  
```txt
type: subject

body

footer
```

## Type

Please choose the most appropriate type for the commit message.
- feat: a new feature
- fix: a bug fix
- docs: changes to documentation
- style: formatting, missing semi semi colons. etc; no code change
- refactor: refactoring production code
- test: adding tests, refactoring test; no production code change
- chore: updating build tasks, package manager configs, etc; no production code change

## Subject

Subject is a short title similar to a news title short, simple and conclusive. Note that imperative tone is preferred. Usually, not more than 50 characters.  

## Body

Body is an optional part of the commit as it is only needed when your commit messages requires a little more explanation and context. The body should explain `what` and `why`, not `how`.  

## Footer

Footer is optional and is used to reference issue tracker IDs.  

## Example

```txt
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequenses of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

## Reference

- Udacity git style guide [link](https://udacity.github.io/git-styleguide/)
