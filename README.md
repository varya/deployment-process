## Deployment process

Project development cycle
  * Development
  * Testing
  * Production

Server structure (cluster)

Veriants for automation
  * Script
  * Version control system
    * Run on your own
    * Deploy by push
    http://ftploy.com/
  * Combinations
    * Partial deployment by third-party service
    http://beanstalkapp.com/
  * Packadges
    * !!easy to revert!!
    * debian packadge
    https://www.pitt-pladdy.com/blog/_20120306-090055_0000_Debian_packaging_for_site_deployment/
    http://blog.rajatpandit.com/2011/12/19/packaging-up-websites-for-easy-deployment/
    http://stackoverflow.com/questions/15126457/debian-packages-versus-fabric-deployment

Deployment from TeamCity
http://www.geekytidbits.com/web-deploy-ms-deploy-from-teamcity/

Hubot
https://github.com/github/hubot/tree/master/docs

Web features

  * Backend and frontend
  * Invalidate frontend? How do we do this?

### Frontend evolution at Yandex
by Sergey Berezhnoy http://tech.yandex.ru/events/yac/2011/talks/33/

A cluster for static files
`img.yandex.net`
Machines in the clusted are specially tuned for static files. Eternal cache.

Eternal cache saves resources, but you face a problem with cache invalidation.


### TODO
http://docs.fabfile.org/en/1.8/
http://css-tricks.com/deployment/
Study Jenkins http://jenkins-ci.org/
https://github.com/capistrano/capistrano/wiki
