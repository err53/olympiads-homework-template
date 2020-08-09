# olympiads-homework-template

A template repository that includes a Github Action to download Olympiads Homework

This runs automatically hourly and upon any non-Action pushes

## Usage

1. Create a new repo on Github, preferrably private (make sure not to add a README or LICENSE, otherwise you might have merge conflicts)
1. Add your login email and password to the new repo's secrets as `EMAIL` and `PASS` respectively
1. Clone this repository to your computer, optionally deleting `.git`
1. Rename the existing remote origin in the cloned folder to something else: `git remote rename origin upstream`
1. Add your repo as the origin
1. Push

## Updating

1. Pull updates from your own repo: `git pull`
1. Pull updates from this repo: `git pull upstream master`
1. Resolve any merge conflicts
1. Push
