# GIT Basic commands

## About
	A note for my carrer using github as part of my journey.

### Configuring github(name,email)

```git

$ git configure --global user.name "Your Name"
$ git configure --global user.email "YourEmalAdd@email.com" 

```

### Intialize git repository in your working directory
```git

$ git init 

```
### Adds the files in the Local repository and stages them for commit
```git

$ git add .

```
### Commiting files in you've staged, Tracked Changes and prepare them to be pushed to the remote repository
```git

$ git commit -m "message or activity" .

```

### Add new remote repository.
```git

$ git remote add origin   https://github.com/kataps/sampleRepo.git

```

### Pushing changes in your local repository to GitHub.
```git

$ git remote add origin https://github.com/kataps/sampleRepo.git

```
### Cloning an Existing Repository
```git

$ git clone https://github.com/kataps/sampleRepo.git

```