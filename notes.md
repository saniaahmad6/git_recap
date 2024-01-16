

on local's main, sync with upstream's main
git fetch --all --prune
git reset --hard upstream/main
git push origin main


git pull upstream main
git push origin main


staged to untracked:
git restore --staged filename

reset to a commit:
git reset commitno

squash commits:
git rebase -i lastneededcommitno

pick or squash

git fetch --all ->fetches everything from remote
git branch -r -> remote branches



