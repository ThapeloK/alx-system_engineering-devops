# 0x0A Configuration management

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/ThapeloK/alx-system_engineering-devops/0x0A-configuration_management)

## Synopsis

In this project, I started working with Puppet as a configuration management
tool. I practiced writing Puppet manifest files to create a file, install a
package, and execute a command.

******************************************************************************
Table of contents
=================

<!--ts-->
   * [Synopsis](#synopsis)
   * [Table of contents](#table-of-contents)
   * [Tasks](#tasks)
   * [Author](#author)
<!--te-->

******************************************************************************

## Tasks :page_with_curl:

* **0. Create a file**
  * [0-create_a_file.pp](./0-create_a_file.pp): Puppet manifest file that
  creates a file `holberton` in the `/tmp` directory.
    * File permissions: `0744`.
    * File group: `www-data`.
    * File owner: `www-data`.
    * File content: `I love Puppet`.

* **1. Install a package**
  * [1-install_a_package.pp](./1-install_a_package.pp): Puppet manifest file
  that install puppet-lint version 2.1.1.

* **2. Execute a command**
  * [2-execute_a_command.pp](./2-execute_a_command.pp): Puppet manifest file
  that kills the process `killmenow`.


******************************************************************************

## Author:
* Thapelo Khantsi @[ThapeloK](https://github.com/ThapeloK)

