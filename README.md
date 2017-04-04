# git-rerere

## Reuse recorded resolution of conflicted merges

### Description
In a workflow employing relatively long lived topic branches, the developer sometimes needs to resolve the same conflicts over and over again until the topic branches are done (either merged to the "release" branch, or sent out and accepted upstream).

This command assists the developer in this process by recording conflicted automerge results and corresponding hand resolve results on the initial manual merge, and applying previously recorded hand resolutions to their corresponding automerge results.


### How to enable it?
Use this command:
```bash
git config rerere.enabled true 
```

> For more information head to [rerere docs](https://git-scm.com/docs/git-rerere).

