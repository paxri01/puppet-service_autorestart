# service_autorestart

[![Build Status](https://travis-ci.org/EncoreTechnologies/puppet-service_autorestart.svg?branch=master)](https://travis-ci.org/EncoreTechnologies/puppet-service_autorestart)
[![Puppet Forge Version](https://img.shields.io/puppetforge/v/encore/service_autorestart.svg)](https://forge.puppet.com/encore/service_autorestart)
[![Puppet Forge Downloads](https://img.shields.io/puppetforge/dt/encore/service_autorestart.svg)](https://forge.puppet.com/encore/service_autorestart)
[![Puppet Forge Score](https://img.shields.io/puppetforge/f/encore/service_autorestart.svg)](https://forge.puppet.com/encore/service_autorestart)
[![Puppet PDK Version](https://img.shields.io/puppetforge/pdk-version/encore/service_autorestart.svg)](https://forge.puppet.com/encore/service_autorestart)
[![puppetmodule.info docs](http://www.puppetmodule.info/images/badge.png)](http://www.puppetmodule.info/m/encore-service_autorestart)


#### Table of Contents

1. [Description](#description)
2. [Setup - The basics of getting started with service_autorestart](#setup)
    * [What service_autorestart affects](#what-service_autorestart-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with service_autorestart](#beginning-with-service_autorestart)
3. [Usage - Configuration options and additional functionality](#usage)
4. [Limitations - OS compatibility, etc.](#limitations)
5. [Development - Guide for contributing to the module](#development)

## Description

This module solves the problem of configuring a service to automatically restart itself
in case the service fails or dies. In Windows this is called "Service Recovery" or
"Service Failure" and can be found in the Service configuration dialog under the "Recovery"
tab. On Linux systems this is simply a parameter on the service unit file in SystemD.

## Setup

### What service_autorestart affects **OPTIONAL**

If it's obvious what your module touches, you can skip this section. For example, folks can probably figure out that your mysql_instance module affects their MySQL instances.

If there's more that they should know about, though, this is the place to mention:

* Files, packages, services, or operations that the module will alter, impact, or execute.
* Dependencies that your module automatically installs.
* Warnings or other important notices.

### Setup Requirements **OPTIONAL**

TODO:
- Resource (`puppetlabs/resource_api`) API if using Puppet 5 or older


### Beginning with service_autorestart

The very basic steps needed for a user to get the module up and running. This can include setup steps, if necessary, or it can be an example of the most basic use of the module.

## Usage

Include usage examples for common use cases in the **Usage** section. Show your users how to use your module to solve problems, and be sure to include code examples. Include three to five examples of the most important or common tasks a user can accomplish with your module. Show users how to accomplish more complex tasks that involve different types, classes, and functions working in tandem.

## Reference

This section is deprecated. Instead, add reference information to your code as Puppet Strings comments, and then use Strings to generate a REFERENCE.md in your module. For details on how to add code comments and generate documentation with Strings, see the Puppet Strings [documentation](https://puppet.com/docs/puppet/latest/puppet_strings.html) and [style guide](https://puppet.com/docs/puppet/latest/puppet_strings_style.html)

If you aren't ready to use Strings yet, manually create a REFERENCE.md in the root of your module directory and list out each of your module's classes, defined types, facts, functions, Puppet tasks, task plans, and resource types and providers, along with the parameters for each.

For each element (class, defined type, function, and so on), list:

  * The data type, if applicable.
  * A description of what the element does.
  * Valid values, if the data type doesn't make it obvious.
  * Default value, if any.

For example:

```
### `pet::cat`

#### Parameters

##### `meow`

Enables vocalization in your cat. Valid options: 'string'.

Default: 'medium-loud'.
```

## Limitations

In the Limitations section, list any incompatibilities, known issues, or other warnings.

## Development

In the Development section, tell other users the ground rules for contributing to your project and how they should submit their work.

## Release Notes/Contributors/Etc. **Optional**

If you aren't using changelog, put your release notes here (though you should consider using changelog). You can also add any additional sections you feel are necessary or important to include here. Please use the `## ` header.
