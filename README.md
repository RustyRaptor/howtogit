# Getting Started

## Git
First we need to get familiar with git. 
1. Run through this git tutorial real quick (excuse the single swear word at the top. It is the simplest tutorial I can find though.)
    - https://rogerdudler.github.io/git-guide/
2. Use what you just learned to work on this repo.
    - Fork this repository to your account.
        - Click "fork" at the top right-ish of the github page.
        - Select your account to fork to
        - now you have your own branch of the repo to work on. 
        - clone your repo
            - copy the https clone link at the top rightish
            - run this command
```bash
                git clone linkyoucopiedhere
```

        - now you have your repo in a folder where you cloned it. 
        - Make some changes to it
            - edit the README.md file
            - add some text to it somewhere.
	    
        - stage your changes
```bash
            git add .

            # the "." at the end indicates that we want
            # to stage all the changes in the current folder
            # this is usually what we want to do. 
            # Sometimes we might want to stage a specific file
```

        - commit your changes. This will finalize the changes and document them
            ```bash 
            git commit -m 'this is a commit message. you should typically put something descriptive of your changes here :)'
            ```
        - now push your changes
```
git push

# sometimes it may ask for a username and password if it's a private repository.
# it may also ask you to enter your details so it can sign your commits (this is one time only)
```

    - Review the changes on github.
    - Finally we want to make a pull request to the master repository (the one on my account)
    	- Go to your own repository and at the top click "new pull request"
    	- Create a new pull request
    		- The source repository should be your own.
    		- The target repository should be the one under RustyRaptor
    		- Select the Master branch of both repositories
    		- Create the merge request
    		- Review and make sure you see the commits you made
    		- add a description to your pull request explaining what changes you made. 
***Congrats this is all you need to know to be able to collaborate on our code. ***
