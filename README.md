# Getting Started

## Git
First we need to get familiar with git. 
1. Run through this git tutorial real quick (excuse the single swear word at the top. It is the simplest tutorial I can find though.)
    - https://rogerdudler.github.io/git-guide/
2. Use what you just learned to work on this repo.
    - Fork this repository to your account.
        - Click "fork" at the top right-ish of the gitlab page.
        - Select your account as the namespace.
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
			- I choose here. - Maggie
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
            ```bash
            git push

            # sometimes it may ask for a username and password if it's a private repository.
            ```

    - Review the changes on gitlab.
    - Finally we want to make a pull request to the master repository (the one on the ETV account)
    - Go to your own repository and on the left panel click "merge requests"
    - Create a new merge request
    - The source repository should be your own.
    - The target repository should be the one under ETVAmericaNavySBIR
    - Select the Master branch of both repositories
    - Create the merge request
    - Review and make sure you see the commits you made
    - add a description to your merge request explaining what changes you made. 
***Congrats this is all you need to know to be able to collaborate on our code. ***

## NodeJS
- Install the LTS version of NodeJS
    - We use the LTS version so we avoid updates breaking our software during development.
- Run the hello world application from here 
    - https://nodejs.org/en/docs/guides/getting-started-guide/
    - run this command in the folder where you are storing the code you copied from the page.
    ```bash
    node app.js
    ```
    - This is a simple nodeJS web application.
    - It's the bread and butter of web application development. 
    - Much of what we do will be built upon something like this. 

## Yarn
Yarn is used to manage our project and it's a package manager to manage all the javascript libraries we use. 

- Here is a good yarn tutorial. 
    - https://flaviocopes.com/yarn/ 

