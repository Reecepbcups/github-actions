# github-actions

## runs on

```bash
Use ubuntu-latest, windows-latest, or macos-latest
# https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners

Pre installed software found at:
# https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners#preinstalled-software
```

## events

```bash
events:
- push (commit), 
- pull_requests, 
- create (branch or tag), 
- fork (repo forked),
- issue (issue opened, deleted, etc)
- issue_comment (Issue or PR comment)
- watch (repo was starred)
- discussion
- workflow_dispatch (manual trigger)
- repository_dispatch (REST API requests work flow)
- schedule (cron)
- workflow_call (called by other workflows)
- other: https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows
```

## actions

```bash
Actions are complex series of steps simplified into less code. While you could manually do it with a run: | of commands, its easier to do with actions typically.
```
