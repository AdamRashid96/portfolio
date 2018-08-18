# portfolio-template
CS Portfoio Project

In this assignment you will create a new web page to host the APCS projects you work on this year. As you finish a project
you will update your portfolio project page with references to the new work (to be done later). For this assignment, you will create 
a short bio about yourself (that you are comfortable being available public on the internet). This will be done using HTML markup.

# Goals
1. Introduce you to the git workflow.
2. Introduce you to some basic HTML.
3. Create a central location to show off the work you've done for APCS.

## Prerequisites
You will need an activated github account. (Should have already completed this step.)

## Steps

* You should have accepted the assignment at this point. Github will have already created the repository. The next step will be to clone the repository on your local machine.
* Open powershell and change directory, `cd`, to c:\users\APCS\java
* Perform a `git clone`, you obtain the clone address from your projects page.
** change directory into the new directory git created, it should be something like `cs-portfolio-username` 
** This step only needs to be done once. set the `user.name` and `user.email`. This needs to be done otherwise you won't be able to check code in,
*** `git config user.emal "youremal@sccs-stu.net"`
*** `git config user.name "your_username"`
* Create a new file named `index.html` in the `cs-portfolio-username` directory that was created from your clone step.
* Update the new index.html file using `sublime` with the template html below and customize it to your liking. Save changes.
* Perform git check-in steps below 
* 

## index.html template
```
<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
<body>
<p>Not Swett</p>

<p>
Interesting stuff about me....
</p>
<table>
  <tr><th> Project </th><th> Demo Link </th><th>Code Base Link </th></tr>
  <tr><td> Frist Proj TBD </td><td> N/A </td><td> N/A </td></tr>
</table>
</body>
</html>
```

## git "check-in" steps:
Generally, the process looks like:
Add new files, commit those files for a check-in, push the check-in to the master copy.

Add\Commit\Push
These are the steps you'll follow for a basic git check-in:
* Everything new that you've created in the directory: 
** `git add .` -OR- `git add theSpecificfile.ext`
* Bundle the added files in a commit:
** `git commit -m "some message to tag with the check in"`
* Finally persist your changes to github:
** `git push`
*** (You should be prompted to enter your github username and password)
