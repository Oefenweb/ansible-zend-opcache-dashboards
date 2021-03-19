## zend-opcache-dashboards

[![CI](https://github.com/Oefenweb/ansible-zend-opcache-dashboards/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-zend-opcache-dashboards/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-zend--opcache--dashboards-blue.svg)](https://galaxy.ansible.com/Oefenweb/zend_opcache_dashboards)

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
