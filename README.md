docker-centos-jenkins-slave-with-swarm
======================================

A docker container based on Centos (7), ready to run as a jenkins slave with java/maven/git/mercurial.

Auto discovers jenkins master.

Built with Ansible.

Credits
=======

* The ansible maven installation is adapted from the galaxy role [groover.maven](https://galaxy.ansible.com/list#/roles/458)
* The jenkins swarm client stuff is adapted from the [maestrodev build-agent](https://github.com/maestrodev/docker-images/blob/master/build-agent/)
