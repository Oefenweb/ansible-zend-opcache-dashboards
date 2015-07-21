## zend-opcache-dashboards

[![Build Status](https://travis-ci.org/Oefenweb/ansible-zend-opcache-dashboards.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-zend-opcache-dashboards) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-zend--opcache--dashboards-blue.svg)](https://galaxy.ansible.com/list#/roles/4436)

Set up Zend [OPCache](http://php.net/manual/en/book.opcache.php) Dashboards.

#### Requirements

None

#### Variables

* `zend_opcache_dashboards_install_dirs` [default: `[]`]: Directories to install zend-opcache-dashboards to (e.g. `/var/www`)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - zend-opcache-dashboards
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-zend-opcache-dashboards/issues)!
