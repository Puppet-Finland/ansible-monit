# ansible-monit

An ansible role that install and configures monit

# Usage

By default this role Manage monit including monitrc. Monitrc management can be 
disabled, e.g. to enable integration with Puppet-Finland/monit Puppet module:

    monit_manage_config: false

# Operating system support

This module has been tested on

* Ubuntu 16.04
