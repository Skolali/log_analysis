[Log Analysis](https://github.com/Skolali/log_analysis)

@Shreyaswini Kolali

# About

  - This is the third project for the Udacity Full Stack Nanodegree. In this project, a large database with over a million rows is explored by building complex SQL queries to draw business conclusions for the data. The project mimics building an internal reporting tool for a newpaper site to discover what kind of articles the site's readers like. The database contains newspaper articles, as well as the web server log for the site.

# Installations Required

You will need:
  - [Python3](https://www.python.org/)
  - [Vagrant](https://www.vagrantup.com/)
  - [VirtualBox](https://www.virtualbox.org/)

# Set Up
1. Install Vagrant And VirtualBox
2. Clone [this](https://github.com/udacity/fullstack-nanodegree-vm) repository

# To Run
Launch Vagrant VM by running vagrant up, you can the log in with vagrant ssh

To load the [data](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip), use the command psql -d news -f newsdata.sql to connect a database and run the necessary SQL statements.

The database includes three tables:

- Authors table
 - Articles table
- Log table

To execute the program, run python3 [log.py](https://github.com/Skolali/log_analysis/blob/master/log.py) from the command line.
