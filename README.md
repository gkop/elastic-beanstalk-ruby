elastic-beanstalk-ruby
======================

Better practices for running Ruby on Elastic Beanstalk using Amazon's AMI

Features
--------

* Follow bundler best practices for deployment
* Bundle gems from git without sacrificing deployment speed
* Allow you to use whatever version of rake you need
* No need to maintain your own AMI

Instructions
------------

Copy the .ebextensions directory into the toplevel of your application source tree, add it to git, and push to Elastic Beanstalk.

Notes
-----

Tested on the 64-bit Elastic Beanstalk AMI for Ruby - ami-1bf9de5e .
