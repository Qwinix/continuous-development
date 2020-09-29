# Qwinix Continuous Development Training Repository

In this repository you will find the various assignments that you will need to complete, in order to complete the various continuous development programs offered by Qwinix's Continuous Development Initiative.

## Working with this repository

In order to work with this repository, you will need to have your own fork. Fork effectively crate your own copy of the repository under your own account, in this way everybody will be able to perform assignments and control access to their own fork without impacting the original copy, also known as your `upstream` remote.

To learn more about Forking check out this [official GitHub Guide](https://guides.github.com/activities/forking/).

## Quick steps to setup.

After you've created a fork in your account by hitting the Fork button in Qwinix's repo, clone your own copy locally:

```bash
# git clone git@github.com:{{ your GitHub Username}}/continuous-development.git
# cd continuous-development/
# git remote add upstream git@github.com:Qwinix/continuous-development.git
# git fetch upstream
# git checkout -b {{ branch for your assignment }} origin/{{ branch for your assignment }}
# git pull upstream upstream/{{ branch for your assignment }}
```

Completing these steps will make sure you have the latest version of the assignment in your own copy of the repository.

Now complete the assignment as you normally would, and commit and push all changes to your repo as you normally would.