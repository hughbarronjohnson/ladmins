# ladmins
Intro Docker project for Linux Admins

## Overview
This project produces a very basic Apache webserver running PHP to show as an example for web development using containers

## Usage 

The docker image can be built by running:

```
docker build --tag="<org_id>/<image_name>" .
```

Now, just execute the new image:

```
$ docker run -dP --name="app-local-test" <org_id>/<image_name> 
```


## Author

  * Barry Johnson (<cyclist@clemson.edu>)
