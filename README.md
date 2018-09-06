## Project Setup at Local

````
    ng new hello-world
````

````
    ng serve 
````

## Share project at Github
* Create Repository at github.
* git remote add origin https://github.com/junkbin/hello-world.git


## Output to whole world
* Library/Module/Package `https://github.com/angular-schule/angular-cli-ghpages`
````
    npm i angular-cli-ghpages --save-dev
````

````
    ng build --prod --base-href "https://USERNAME.github.io/REPOSITORY_NAME/"

    ng build --prod --base-href "https://junkbin.github.io/hello-world/"
````


````
    ngh --dir=dist/[PROJECTNAME]

    ngh --dir=dist/hello-world
````

````
    https://junkbin.github.io/hello-world/
````

