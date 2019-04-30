# ladmins
Intro Docker project for the CCIT Linux Admins meeting

## Overview
This project produces a very basic Apache webserver running PHP to show as an example for web development using containers

## Usage 

The docker image can be built by running:

```
docker build --tag="sometagname" .
```

Now, just execute the new image:

```
$ docker run -p 80:80 --name="app-local-test" sometagname 
```


## Author

  * Barry Johnson (<cyclist@clemson.edu>)
