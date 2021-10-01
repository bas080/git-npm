# git-npm

Make it easier and safer when working with git and npm.

## Installation

Simply add `git-npm` to one of the directories in your `$PATH` and make sure it
is executable.

## Usage

```bash bash
git-npm help
```
```
Synopsis:
  git-npm [subcommand]

Subcommands:
  completion 
  help 
  publish [<branch>]
    Publish specific branch to the NPM repository.
  tags [<branch>]
    Create remote tags for (current) branch.
```

## Build

Building the project requires [bashionista][1]

```bash bash
./lib/git-npm bundle > git-npm
```

## Test

```bash bash
shellcheck ./lib/git-npm
```

## Stackoverflow

Might help people with this [stackoverflow question][2].

[1]:https://github.com/bas080/bashionista
[2]:https://stackoverflow.com/questions/38460008/automate-git-commit-versioning-tag-by-npm-node/69396023#69396023
