# Task #1 Hello world

## Clone project 


`git clone https://github.com/yuri-vodolazsky/tasks.git`


Command above requests your Github credentials (username & password)
and in success case will push the project and create dir `tasks` for it,
which can be seen in current directory by typing command 

`ls` 

in terminal. Command above displays content of the current directory (`l`i`s`t of files and sub directories).

In order to work with project one need to "go into" this project's directory using command


`cd tasks`


which `c`hanges `d`irectory to what you says, in case above to `tasks`.
To be sure that you are in the right place you can type: 

`pwd`

On my computer output of the command above is following: 

```yuri@yuri-Lenovo-G580:~/proj/tasks$ pwd
/home/yuri/proj/tasks```


## Setup WEB server


Please run following command in terminal, which `i`nstall libraries required for this project:

`npm i`

We ask `n`ode `p`ackage `m`anager to `i`nstall project's dependecies (libraries which are just programs written by other coders, which we are going to use in order to do not reinvent a wheel).
You can ensure that required packages have been downloaded and saved in current folder again by using `ls` command already mentioned earlier. In my case output is following: 

```yuri@yuri-Lenovo-G580:~/proj/tasks$ ls
index.html  node_modules  package.json  package-lock.json  README.md  task1.html  task1-modified.html
```

## Start web server

This can be done using following command: 

`./node_modules/.bin/http-server`

Which should produce following output:

```yuri@yuri-Lenovo-G580:~/proj/tasks$ ./node_modules/.bin/http-server 
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
  http://192.168.100.16:8080
  http://10.27.14.18:8080
  http://10.22.0.142:8080
  http://10.30.11.10:8080
Hit CTRL-C to stop the server
```

Open first URL above (http://127.0.0.1:8080) in the browser and go to the first task



