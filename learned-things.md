# Learned Things
This repository contains details about the things I've learned till...

## Git and Commands

**git config --global user. name** _"name"_ 

**git config --global user.email**  _"email"_ 

    Above commands allow user to add/set their user name and email

**git init** 

    Use to initialize git

**git status**

     Use to check status

**git add** _"file_name"_

    Add changes to working directory in stage area

**git commit** 

    Use to save changes in local repository

**git remote add origin** _"git_link"_

    To add a new remote repository

**git remote set-url origin** _"git_link"_

    To change the url of an existing remote repository

**git push -u origin** _"master"_

    It will push code to master branch

**git checkout -b** _"branch_name"_

    Command use to create new branch and switch to that branch

**git diff**
    
    Use to check changes between commit and working tree

**git commit**

    Shows the list of all commits

**git reset**

    Use to undo local changes to the state of Git repo

**git stash**

    Temporarily shelves changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on.

**git stash pop**

    Use to re-apply the previous commit

**git merge**

    Join two or more development histories together

****
        
## React


**default vs named export**

 `default export` 
    
    1.  In default export keyword "default" is used to export value.    
            default export 'function_name'

    2.  A single value (class, object and function) is exported in default export.

    3.  In default export, any name can be used at the time of import. 

`named export` 
    
    1.  In named export simply write "export" to export value. 
            default export 'function_name'

    2.  Mulitple values (class, object and function) can be exported in default export.

    3.  In named export, same name is used at the time of import. 

**type script**
       
   -     In react type script, allow developer to develop strong-typed components. 

   -     Props and state of components are indentifiable.

**props**
    
   -     Props are the object used to store the value of attributes.
   -     Props are passed to the component in the same way as arguments are passed in a function.

**useState**

    The useState() is a Hook that allows you to have state variables in functional components.

```javascript
const [state, setState] = useState(initialstate)
```

****




