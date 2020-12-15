# Messing with the Devilbox
Getting devilbox ready for Joomla4


## What is a devilbox?

Devilbox is a sophisticated lamp stack offering much the same facilities as Wamp or Xamp.  It provides all the bnasic ingredients needed to host a website, including a website built on a Content Management System like Joomla or that other one...

Everything to do with Devilbox can be found here: http://devilbox.org/

for documentation:
https://devilbox.readthedocs.io/en/latest

for the github repo
https://github.com/cytopia/devilbox


To code(...cough) along with us tonight, you will need to download the devilbox package.

2 ways to do this:

1. pull using git (needs git running on your system)

traverse to the location you want to store the app, then

```
git clone https://github.com/cytopia/devilbox
```

2. Download the zip and unpack it to where you want to run it from
https://github.com/cytopia/devilbox/archive/master.zip

Rename the folder from devilbox-master to devilbox.

Then from eother method, inside the root of devilbox, rename the "env-example" file 
to
".env"

Then from a windows command or Powershell window (as administrator), traverse to the root of your devilbox folder.

```
docker-compose up -d
```



