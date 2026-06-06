# jj-guide.llm

A Claude Code / Agent skill for working safely and effectively with [Jujutsu (jj)](https://github.com/jj-vcs/jj), a Git-compatible VCS with mutable commits, automatic snapshotting, no staging area, and first-class conflicts.

This is a fork of [mtaran/jj-guide](https://github.com/mtaran/jj-guide) which does not currently have any modifications.

Commits pushed to the `techcable` branch have some basic verification for correctness and security.
I have done a brief review by hand and asked claude for a more thorough review.
I plan to review all upstream updates before merging into this branch.
Github will enforce a linear commit history and prevent unauthorized/automatic updates.

## Acknowledgements
The upstream repository where this is forked from is [mtaran/jj-guide](https://github.com/mtaran/jj-guide).

Here is a shortened list of the repositories this code is based on:

- [mtaran/jj-guide](https://github.com/mtaran/jj-guide) (*directly forked from*)
- [plasticbeachllc/jj-skipper](https://github.com/plasticbeachllc/jj-skipper)
- [danverbraganza/jujutsu-skill](https://github.com/danverbraganza/jujutsu-skill)
- [kawaz/claude-plugin-jj](https://github.com/kawaz/claude-plugin-jj)
- [jj official documentation](https://github.com/jj-vcs/jj/tree/main/web/docs/src/content/docs) ([for humans](https://www.jj-vcs.dev/latest/))


See the upstream README for [more detailed acknowledgements](https://github.com/mtaran/jj-guide#acknowledgements), including a description of what was taken from where.

## License
MIT, just like upstream.
