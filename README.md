# Developer Setup
### Set up git
##### Create ssh key for git
```ssh-keygen -t rsa -b 4096 -C "ctmillaz@gmail.com"```

##### Add ssh key to git site ssh key location
##### Add ssh key to ssh config file
```
Host github
    HostName https://github.com
    User <user>
    IdentityFile ~/.ssh/<name of public file>.pub
    StrictHostKeyChecking no
```

##### Setup git global configs
```git config --global user.email "<Your email>"```

```git config --global user.name "First name and Last name"```

##### Create credentials file
```nano ~/.git-credentials```

##### Put this in credentials file
```https://<username>:<token>@<git site>```

```https://ctmillaz:<token>@https://github.com/```

##### Cache git credentials
```git config --global credentials.helper 'store --file ~/.git-credentials'```

##### Clone repo
```git clone <repo url>```