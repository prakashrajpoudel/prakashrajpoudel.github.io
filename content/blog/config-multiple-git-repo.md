+++
title = "Config Multiple Git Repo"
date = "2023-01-25T11:30:02-05:00"

#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."
description = "Configure to push and pull from two different git repo. github and bitbucket with different creds"
tags = []
+++

- Configure bitbucket as default git repo
- Configure `git` to talk to github
    - Setup github public key
    - Configure your ~/.git/config
    ```
        Host github.com
            Hostname github.com 
            IdentityFile ~/.ssh/id_rsa_github
            IdentitiesOnly yes
    ```
- Now you can seamless do github and bitbucket without doing extra work everytime
