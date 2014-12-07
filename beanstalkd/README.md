Beanstalkd
================

##Instructions
All the configuration is placed in the vars/main.yml.
The values you see are the default one.

##Options

  - ip: The ip the Beanstalkd is listening to.
  - port: The port the Beanstalkd is listening to.
  - start: If the Beanstalkd should start at the boot of the machine.
  - persistent: If Beanstalkd should persist the queue
  - persistent_file: Where Beanstalkd is going to persist that queue
