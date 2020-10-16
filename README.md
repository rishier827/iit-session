
# IIT session


## Table of Contents
* [Setting Up the Project](#setting-up-the-project)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Social Media](#social-media)
## Setting Up the Project
These are the instructions for setting up the project locally. If you are hoping to contribute to the project, this will help you do all the changes locally.

### Fork the project
You can fork the project by clicking the fork button on the top right corner of the page.
![Screen-Recording-2020-05-23-at-8](https://user-images.githubusercontent.com/35812345/82733467-a119c380-9d31-11ea-9a22-882c5c220c8c.gif)

### Clone the project you forked
The URL of the project you cloned would look like 
(Replace [your_username] with your github username.) 
```https://github.com/[your_username]/JapuraEcon```

You can clone it to your local machine by typing and entering the below command in your terminal. (Replace [your_username] with your github username.) git clone ```https://github.com/[your_username]/JapuraEcon```

# Installation
* `npm install`
* install sequelize-cli 
`npm install --save-dev sequelize-cli`
* create D `dev_db` database inside your database
* run `sequelize db:migrate` to migrate data
* `npm start`
To run use this link
* http://localhost:3000/users


## Reporting Issues

We use GitHub Issues as the official bug and new feature tracker for the Official JapuraEcon website.

These are the steps you must follow when you are going to report a bug or suggest a new feature to the project.
1. Go to the issues tab.
``` https://github.com/sigzonicLabs/japura-econ-nodejs/issues```
2. Click "New Issue" Button.
3. Then you will be prompted a menu with options as "Bug report" and "Feature request".
4. You can select either option based on the bug or feature you are going to report as an issue.
5. After selecting the relevant option, provide a title for your issue.
6. Next step is to fill out the template with accurate information about the bug or feature.

Here are some advices for our users that want to report an issue:
1. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
2. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.
3. If it is a new feature, try to explain it in a manner in which the reader would be able to get a fair understanding about it.
 
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
### Bit for your knowledge regarding upstream n merging
first check whether ur *forked(rishier827/japura-econ-nodejs)* repository and *original(sigzonicLabs/japura-econ-nodejs)* were there,

``` git remote -v ```
If not please add original repository from this command, If its only showing your forked account then you have to add upstream

<img width="840" alt="image" src="https://user-images.githubusercontent.com/35812345/83352509-8961c100-a369-11ea-8847-cc3bf510c977.png">

```git remote add upstream https://github.com/sigzonicLabs/japura-econ-nodejs```
After adding then it will display like this

<img width="823" alt="image" src="https://user-images.githubusercontent.com/35812345/83352531-b1e9bb00-a369-11ea-83fc-01acf17296de.png">

Finally fetch and merge.

```git fetch upstream```

``` git merge upstream/master```

## License
[MIT](https://choosealicense.com/licenses/mit/)
