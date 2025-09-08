# z-test-repo

A repository to try out various GitHub features

## creating and merging a pull request

*.github/workflows/make_pr.yml*

There are some things I need to do automatically, so I want to create
the PR and merge it if everything goes right. This is a bit tricky
because things are in different places.

## labeling created or closed PRs

Uses *.github/bin/labeler*, a Perl script, to do everything since the
command lines were getting too weird. It still uses quite a bit of *gh*
on the inside.

* label new PRs with basic labels
* in closed PRs that were merged, remove some status and priority labels and add others
* in closed PRs that were not merged, mark it as rejected.

This is mostly proving that I can do it with a program.

This one is tricky because GitHub has a trigger for "Closed", but you
have to dig deeper to see why it was closed.

## Other crazy things

Sometimes I use this to test various automations before I try them on other repos.
