# quiz-2015

## How to Build & Install

- Software requirements:

	+ nodejs 
	+ npm

 + Note: Both can be installed from (http://nodejs.org/download/)
 + Note: If you are using Ubuntu package manager we recommend to use [Chris Lea package](http://www.ubuntuupdates.org/ppa/chris_lea_nodejs):
<pre>
	sudo apt-get install make g++
        sudo apt-get install software-properties-common python-software-properties
        sudo add-apt-repository ppa:chris-lea/node.js
        sudo apt-get update
        sudo apt-get install nodejs
</pre> 

- Clone Quiz repository:

<pre>
git clone https://github.com/aalonsog/quiz-2015.git
</pre>

- Install the dependencies:

<pre>
cd quiz-2015/
npm install
</pre>

- Configure the ENV variable for the database depending on the one you want to use

  + Postgres: DATABASE_URL=postgres://user:passwd@host:port/database
  + SQLite:   DATABASE_URL=sqlite://:@:/

- Configure the ENV variable for encripting the passwords

  PASSWORD_ENCRYPTION_KEY=topsecret

## How to Start the server

<pre>
npm start
</pre>

This command runs the server in port 3000. You can connect to this port using a web browser.
