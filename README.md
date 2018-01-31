# learning-git
Learn Git and GitHub by contributing to this repo!

In the FAQs below we've got a bunch of questions without answers. Do some Googling to find these answers, and create a pull request to have your answer listed here. See the CONTRIBUTING document for more information on how to contribute to this repo.

If you have any other questions not listed here, please raise a PR to have it added. There's no need to answer it unless you want to.

## Git FAQ

- Q: I made a typo in my commit message, how can I __amend__ it?
- A: `git commit --amend` allows you to change the last commit message. You can add a `-m "commit message"` to add a message at the same time.

- Q: Can I see a __log__ of the commits that have been made on this repository?
- A: `git log`

- Q: What are some Graphical User Interfaces(GUI, pronounced "gooey") that I can use with Git? 

- A: GitKraken, SourceTree, Git

- Q: I have accidentally staged something I don't want to commit. Can I __reset__ only that file?

- Q: I would like to see what the repo looked like at a given version. How can i __checkout__ that version?

- Q: How can I see a __diff__ of what's changed in the files I've changed but not committed? How about just the files I've staged?
- A: `git diff` shows the unstaged changes. `git diff --cached` shows the staged changes.

- Q: Can Git __show__ me what's changed in the previous commit?
- A: Type in `git show`.

- Q: How can I `add` only parts of a file I've changed?

- Q: How can I __revert__ a commit?
- A: Use `git reset HEAD~`.

- Q: I keep accidentally adding files I don't want to commit (e.g. compiled code, files with passwords etc.), how can I __ignore__ these files?

- Q: What's the difference between `git pull` and `git fetch`?

- Q: How can I __clean__ the repo of any untracked files, i.e. removing new, unstaged files without manually `rm`ing all of them?

### A bit more challenging questions:

- Q: Windows behaves differently to most operating systems, in particular in how it handles line endings (Windows uses CRLF whereas all other operating systems use just LF). How can I make sure that all commits use the same line endings? What are the consequences of not caring about this?

- Q: I need to change branch, but Git won't let me because I have modified some files. I don't want to commit these yet, can I __stash__ them away for later?

- Q: How can I make it so that `git diff` also displays the diff of new file's I've introduced?

- Q: What's the difference between a `merge` and a `rebase`?

## GitHub FAQ

- Q: How can I see who wrote a specific line in a file, so that I can __blame__ the right person?
- A: 'Git blame <filename>' can ensure the correct person is punished accordingly.

- Q: How can I add collaborators to this project?

- Q: How can I create my own organisation?

- Q: How can I create a project issue tracker?

- Q: How can I create a website for my repository? (Author's note: This violates some sort of universal law: it's free, easy and fast!)

### A bit more challenging questions:

- Q: How can I make it so that GitHub remembers my computer, and doesn't ask for username and password all the time?

- Q: What's the difference between cloning over HTTPS and SSH?

- Q: Would you recommend a different method (simpler perhaps?) for repo maintainers to contribute?

- Q: What are some common branching strategies? What strategy does our `CONTRIBUTING.md` file recommend?
