# Redo commits
  Erase mistakes and craft replacement history

* Undoes all commits after [commit], preserving changes locally
  >$ git reset [commit]

* Discards all history and changes back to the specified commit
  > $ git reset --hard [commit]

CAUTION! Changing history can have nasty side effects. If you
need to change commits that exist on GitHub (the remote),
proceed with caution. If you need help, reach out at
github.community or contact support.