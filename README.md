- GitHub Actions configurations:
    Master / Feature/*
    - Protect matching branches:
        - Require a PR before merging : Master
            - Require Approvals : 2 (technique & Fonctional)
            - Dimiss Approval when new commit is done
        - Require Status Checks to pass before merging : Master
            - job2 example
        - require convesration resolution before merging 
        - Require deployments to succes before merging ( DEV et INT) ==> a tester
        


- Create a template for all github repos:
    - convention naming for commit-message

- manage pull requests:
    - define the number of reviewers
    - define roles of reviewers

- branch protection setting : https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches
