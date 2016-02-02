# hadith-graph
A graph knowledge Hadith of the Prophet Muhammad (صلى الله عليه و سلم)

## How To Contribute

This app is use node, so make sure you have installed it.

Fork this project to your development machine

```
git clone git@github.com:sajadah/hadith-graph.git
```

Then go to working dir

```
cd hadith-graph
```

Next, install dependencies:

```
npm install
```

Run the app:

```
DEBUG=hadith-graph:* npm start
```

For easiness in development, you can install [nodemon](https://github.com/remy/nodemon) in your local machine. nodemon will watch the files in the directory in which nodemon was started, and if any files change, nodemon will automatically restart your node application

After install nodemon, then run:

```
DEBUG=hadith-graph:* nodemon bin/www
```

## Database

Hadith Graph use [OrientDB](http://orientdb.com/) as the primary data store. Type the following command to install Orient:

For OSX

```
brew install orientdb
```

For Linux distro, please read this doc https://www.digitalocean.com/community/tutorials/how-to-install-and-use-orientdb-on-an-ubuntu-12-04-vps
