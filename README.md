# log-analysis-project
## Project Overview
this project is about bulding a reporting tool that well execute queries on newspaper database to find which artical, author get the most viewd 
## instaliton 
1. first thing yuo need to instal vagrant virtual box from [Here](https://www.vagrantup.com/downloads.html/). 
2. dawnload this file and make sure to save it on the desktop  [Here](https://classroom.udacity.com/nanodegrees/nd004-mena/parts/a8609286-c119-4bc5-b9c9-2a3828080114/modules/56f0f4c7-d611-4949-b8d5-e1b9df12d95f/lessons/4cff95e1-3f1c-435a-bc6c-40fcf0d8f884/concepts/0b4079f5-6e64-4dd8-aee9-5c3a0db39840?contentVersion=1.0.0&contentLocale=en-us)   
3. dawnload the database [Here](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip/)  
4.make sure to save the project file with database inside the vagrant folder \fullstack-nanodegree-vm-master\vagrant
5. now you can run the program from the command prompt but its better to use git.bash you can find it [Here](https://git-scm.com/downloads/).  
## running the project
1. Navigate to  folder using the bash interface  `cd your-directory\fullstack-nanodegree-vm-master\vagrant`
2. creates and configures the guest machines(vagrant) tybe `vagrant up` it may take sometime. 
3. Now you will open a connection into a the running Vagrant `vagrant ssh`.
4. dawnload the database to vagrant use `psql -d news -f newsdata.sql` and run it with `psql -d news`
5. Navigate into the vagrant folder using `cd /vagrant`and then to project folder `cd log_project`
6. now you can run the program using `python log-analysis.py`

