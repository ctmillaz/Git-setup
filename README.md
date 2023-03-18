# Developer Setup
### Set up git
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

