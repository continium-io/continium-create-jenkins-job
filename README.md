Continium-Create-Jenkins-Job-Role
=========

This role create a Jenkins Job from files directory in XML file.

Requirements
------------

This role using jenkins_job module. This module require python-jenkins library. Please install python-jenkins module on ansible host.

Role Variables
--------------

This role have five variables in defaults/main.yml file. Set these variables before running.

    job_name: Job's name.
    jenkins_password: Jenkins user password.
    jenkins_url: Jenkins host domain or url.
    jenkins_port: Jenkins host port.


Dependencies
------------

This has no dependency. Just run

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - continium-create-jenkins-job
      vars:
          - job_name: Example_Job
          - jenkins_password: admin
          - jenkins_url: 1.1.1.1
          - jenkins_port: 8080
          - jenkins_user: admin

License
-------

BSD

Author Information
------------------

Emre Aydınsoy. 

DevOps Engineer