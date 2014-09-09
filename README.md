docker-compass
==============

Run compass within a docker container

So instead of running

    $ compass build

You can run 

    $ docker run -ti -v `pwd`:/srv marmelab/compass build
