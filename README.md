# quiz-2015

## How to Build & Install

- Software requirements:

	+ nodejs 
	+ npm
	Note: Both can be installed from (http://nodejs.org/download/)
	Note: If you are using Ubuntu package manager we recommend to use http://www.ubuntuupdates.org/ppa/chris_lea_nodejs 

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

  + Postgres: DATABASE_URL = postgres://user:passwd@host:port/database
  + SQLite:   DATABASE_URL = sqlite://:@:/

- Configure the ENV variable for encripting the passwords

  PASSWORD_ENCRYPTION_KEY = topsecret

- Start the server

<pre>
npm start
</pre>
