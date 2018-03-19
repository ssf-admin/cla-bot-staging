# Staging area of cla-bot

This project contains a staging area for the [cla-bot](https://colineberhardt.github.io/cla-bot) instance that serves the [Symphony Software Foundation hosted projects](https://symphonyoss.github.com).

## Configuration

The bot is configured only to accept contributions from `ssf-admin` GitHub user, see [contributors.json](contributors.json).

The custom message used to add a comment to Pull Requests, in case one of the committers is not included in the list of contributors, is configured in [.clabot](.clabot) file.