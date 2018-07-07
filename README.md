docker-compass
==============

Run compass within a docker container

So instead of running

    $ compass compile

You can run 

    $ docker run -ti -v `pwd`:/srv marmelab/compass compile
