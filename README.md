# 2016Spike

This is our code base we used for 2016.

## Prerequisites
 * [ANT](http://ant.apache.org/bindownload.cgi)
 * An internet connection
    * This is to get all dependencies and IVY dependency manager. Once you have downloaded all dependencies you no longer need an internet connection.

```sh
#run this to get this repository
git clone git@github.com:technomancers/2016spike.git
cd 2016spike
#build the project (the default does not currently deploy to roboRIO)
ant
#use this command to clean up your workspace
ant clean
```