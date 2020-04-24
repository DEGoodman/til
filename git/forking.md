# Quickstart to forking

Most open source projects will have you fork the repository, make your changes, then submit a pull request back to the original project. I found [this][1] slightly more detailed (and very good!) post on forking, but here's a summary of the workflow

1. Navigate to the project you want to contribute to and click 'Fork" button (assuming it's GitHub)
2. You will now have this repo forked in your profile. Clone it to your machine.
3. Set the source repo as a new remote "upstream" so that you can track changes, AKA `git remote add --track master upstream git@github.com:facebook/react-native.git` then fetch.
4. Create a new branch for your changes, make them, add, commit, and push!
5. Submit a PR back to the original repo. Again, GitHub makes this super easy with buttons on the repos.

[1](https://jarv.is/notes/how-to-pull-request-fork-github/)
