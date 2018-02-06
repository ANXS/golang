## ANXS - erlang [![Build Status](https://travis-ci.org/ANXS/golang.png)](https://travis-ci.org/ANXS/golang)

Ansible role which installs Golang

# Overview

This role can be uesd to install Golang on a workstation or server, accessible system-wide or by a single user. It has been tested on Linux (WSL and stock Ubuntu) along with macOS. It probably needs a recent Ansible.

This role is still kinda beta.

# Variables

* `golang_version` defaults to `1.9.2`
* `golang_base_path` defaults to `/opt` but you will want to override this if you are installing as a user
* `golang_cache_path` controls where we cache our downloaded files
* `golang_profile` is a boolean, enabled by default, determines whether or not we install a profile snippet
* `golang_profile_path` controls where the profile snippet is installed
* `golang_profile_file` is the name of the profile snippet
* `golang_user` and `golang_group` are kinda self explanatory


#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ANXS/golang/issues)!
