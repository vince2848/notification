# Notif - The notification package for every python project
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![Build Status](https://travis-ci.com/davebulaval/notification.svg?branch=master)](https://travis-ci.com/davebulaval/notification)

Notif is a easy to use package to send notification from a python script.

Use this package to send during, at the end or when failing of a python script a

    - Slack notification
    - Email notification
    - Channel notification
    - Facebook messenger notification.
    
> Please be careful with your login credential. Use a .env or any other file not publish by your git (configured in .gitignore). Read the [following](https://stackoverflow.com/questions/2397822/what-is-the-best-practice-for-dealing-with-passwords-in-git-repositories) for best pratices

    
Read the documentation at [notificationdoc.ca](https://notificationdoc.ca).

---------

## Installation

```shell script
pip install notif
```


--------------
Unfortunately the `fail_decorator` is not working with the package (for now) with the [Sacred](https://pypi.org/project/sacred/) package.

