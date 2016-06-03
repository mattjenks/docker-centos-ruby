# docker-centos-ruby
Learning about docker, markdown, etc!
Creating a base CentOS 6 image and attempting to understand the pieces.
basis for this learning can be found [here](https://github.com/jdeathe/centos-ssh/blob/centos-7-develop/README.md).

## docker image

The image itself is based on centos6.7.
Tools included are:
*   ruby-2.1.3
*   [rvm](https://rvm.io/)
*   [Supervisor](http://supervisord.org/)
*   [supervisor-stdout](https://github.com/coderanger/supervisor-stdout)




## run interactive shell
    docker run -it containernameorid bash

