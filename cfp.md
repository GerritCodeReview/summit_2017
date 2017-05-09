# Propose a talk about Gerrit Code Review

The User Summit is about people and their experiences
in using Gerrit Code Review for their teams and companies.

We are looking forward to receiving fantastic proposals from industry
experts about how they have used and improved their Development
Pipeline and/or have extended Gerrit with amazing plugins.

Your experience could include as well the entire Continuous
Integration pipeline, including integration with CI (Jenkins or others)
and your issue tracking system.

## How to submit my proposal?

It is very simple, just clone this project, create a Markdown under the
/sessions directory using the template.md as an example and then push for review.

You need to be registered on https://gerrit-review.googlesource.com in order
to be able to be authorized to push changes for review.

**Example:**

```bash
$ git clone https://gerrit.googlesource.com/summit/2017 && (cd 2017 && curl -Lo `git rev-parse --git-dir`/hooks/commit-msg https://gerrit-review.googlesource.com/tools/hooks/commit-msg ; chmod +x `git rev-parse --git-dir`/hooks/commit-msg)
$ cd 2017/sessions
$ cp template.md myamazingtalk.md
$ vi myamazingtalk.md

...

$ git add myamazingtalk.md & git commit -m 'This is my amazing talk'
$ git push origin HEAD:refs/for/master
```

## How my talk is going to be voted and selected?

The voting is opened to everyone that is registered to
https://gerrit-review.googlesource.com.
People will be able to post comments, ask questions and vote for it.

The top 12 rated proposals will become part of the Gerrit User Summit 2017
agenda.
