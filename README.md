# README

MAVENS MANAGER VERSION-2 is a project for (here full description of the project).

Prerequisites

Docker and Docker Compose

Docker: https://www.docker.com/get-started

Docker Compose: https://docs.docker.com/compose/install/

Rails 6 and Ruby 2.7.1

If the local machine hasn't got Ruby installed, RVM would be a common solution to consider.

For installing RVM with default Ruby and Rails in one command, run:

\curl -sSL https://get.rvm.io | bash -s stable --rails

To verify the successful installation:

$ ruby -v

ruby 2.7.1p83 (2020-03-31 revision a0c7c23c9c) [x86_64-linux]

$ rails -v

Rails 6.0.3.3

Requirements

MM Docker project : https://github.com/Flormarys/mm-docker

Setup Environment

Clone this repository using GIT:

$ git clone git@github.com:fernanluis/mm-api-ruby.git

Change to the new folder

$ cd mm-api-ruby

Create in the same path .env file using env-example

To verify if we have the Ruby on Rails files

$ ls

GitHub added a new branch named main. Then we have verify tha branch and also we need showing the hidden.

$ git branch or $ git branch -a

To change of branch

$ git checkout master # Here we have our Ruby on Rails files.

Replace DB variables (and others required) taking into account the MM Docker env variables

Install dependences:

$ bundle install
