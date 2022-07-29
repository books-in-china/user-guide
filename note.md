

1. install python

   suggest to install conda or anaconda


2. https://www.mkdocs.org/getting-started/

   pip install mkdocs

   mkdocs new user-guide && cd user-guide

   mkdocs serve 

       for preview

       ctrl + c to stop the server

3. mkdocs build
        a folder: site will be generated

4. create a new repository in github

5. clone the repository by GitHub Desktop

    rename mkdoc project folder temporially

    clone the repository

    move all files of old mkdoc project into the cloned the repository folder

6. mkdocs gh-deploy

    this will fail by the https authentication of github, but it's ok... we need this to create the branch: gh-pages

7. commit and push by GitHub Desktop

    switch to gh-pages branch first, then commit & push




