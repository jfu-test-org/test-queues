# test-queues

Noats:

- merge queues are available to us
- might be handy for us on busy branches like `test`
- PRs in the queue will automatially sync with base branch (and preceding PRs) 
  - will not merge if there is a merge conflict
- saves us the babysitting of manually merging with test, etc
- can add a new check: is previous build in CircleCI complete? before merging
- branch either has "require merge queue" setting on or off
  - can't manually merge
  - 
- another one
- branch that passes after five minutes
- branch with a merge conflict
- another branch that passes
- 
