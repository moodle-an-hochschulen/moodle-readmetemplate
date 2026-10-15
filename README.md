moodle-[component_pluginname]
=============================

[![Moodle Plugin CI](https://github.com/moodle-an-hochschulen/moodle-[component_pluginname]/actions/workflows/moodle-plugin-ci.yml/badge.svg?branch=main)](https://github.com/moodle-an-hochschulen/moodle-[component_pluginname]/actions?query=workflow%3A%22Moodle+Plugin+CI%22+branch%3Amain)

[A short description of the plugin]


Requirements
------------

This plugin requires Moodle [Version]+

==OPTIONAL==

Additionally, this plugin requires these other third party plugins:

* The Moodle plugin [component_pluginname] which is published on https://github.com/[organisation]/moodle-[component_pluginname] / https://moodle.org/plugins/[component_pluginname].

==END OPTIONAL==


Motivation for this plugin
--------------------------

[The motivation to write this plugin]


==OPTIONAL==

Screenshots
-----------

![[Alt text which describes what is shown on the screenshot]](docs/screenshot.png)

==END OPTIONAL==


Installation
------------

Install the plugin like any other plugin to folder
[path to plugin]

See http://docs.moodle.org/en/Installing_plugins for details on installing Moodle plugins


Usage & Settings
----------------

After installing the plugin, it is ready to use without the need for any configuration.

==OR==

After installing the plugin, it does not do anything to Moodle yet.

To configure the plugin and its behaviour, please visit:
Site administration -> [path to the plugin settings]

There, you find [x] settings:

[Describe the settings]

If you want to learn more about using [plugin type] plugins in Moodle, please see https://docs.moodle.org/en/[plugintype].


Capabilities
------------

This plugin also introduces these additional capabilities:

### [component]/[pluginname]::[capability]

[Short description of the capability and its default assignation]

==OR==

This plugin does not add any additional capabilities.


Scheduled Tasks
---------------

This plugin also introduces these additional scheduled tasks:

### \[pluginname]\task\[taskname]

[Short description of the scheduled task]\
By default, the task is disabled.

==OR==

This plugin also introduces these additional scheduled tasks:

### \[pluginname]\task\[taskname]

[Short description of the scheduled task]\
By default, the task is enabled and runs [the standard schedule].

==OR==

This plugin does not add any additional scheduled tasks.


Message providers
-----------------

This plugin also introduces these additional message providers:

### [component_pluginname]/[messageprovidername]

[Short description of the message provider, which messages it delivers and to whom]\
By default, this message provider is [enabled / disabled / forced on] for the [email / popup / ...] output[s]. [Describe which capability is needed to receive the messages, if any.]

==OR==

This plugin does not add any additional message providers.


Checks API
----------

This plugin also introduces these additional checks to the System status page:

### \[pluginname]\check\[checkname]

[Short description of the check, what it verifies and when it fails]

In the CLI script admin/cli/checks.php, this check can be filtered with its reference `[pluginname]_[checkname]`.

==OR==

This plugin does not add any additional checks to the System status page.


CLI tools
---------

This plugin also provides these additional CLI tools:

### cli/[scriptname].php

[Short description of the CLI script, its purpose and its parameters]

Run it with:

```
sudo -u www-data php [path to plugin]/cli/[scriptname].php [--parameters]
```

==OR==

This plugin does not provide any additional CLI tools.


Expert settings for config.php
------------------------------

There are expert settings without GUI setting which can be defined in config.php to customize this plugin in expert scenarios:

### `$CFG->[component_pluginname]_[settingname]`

[Short description of the expert setting, its possible values and its default value]

==OR==

There aren't any expert settings without GUI setting which could be defined in config.php only.


How this plugin works [ / Pitfalls]
-----------------------------------

[How it works]


==OPTIONAL==

Limitations
-----------

[Describe the scenarios and use cases which the plugin deliberately does not cover or support]

==END OPTIONAL==


Backup & Restore
----------------

This plugin has the following support for backup & restore:

### [Data which is stored by this plugin]

[Describe which data of this plugin is included in course backups and how it is handled during restore, course duplication and course import. Describe the functional limitations, for example when restoring onto another site]

==OR==

This plugin does not store any data which is relevant for / included in backup & restore.


==OPTIONAL==

Security considerations
-----------------------

[Describe the security-relevant aspects of the plugin, for example bundled library files which must not be directly accessible, user-provided content which is not sanitized or capabilities which should be assigned carefully. Describe the measures which the admin should take]

==END OPTIONAL==


==OPTIONAL==

Privacy considerations
----------------------

[Describe the privacy-relevant aspects of the plugin, for example external services or CDNs which are contacted, personal data which is transferred to third parties or data which is stored beyond Moodle's privacy API. Describe to which pages / users this applies and which measures the admin can take]

==END OPTIONAL==


Theme support
-------------

This plugin is developed and tested on Moodle Core's Boost theme.
It should also work with Boost child themes, including Moodle Core's Classic theme. However, we can't support any other theme than Boost.

==OR==

This plugin acts behind the scenes, therefore it should work with all Moodle themes.
This plugin is developed and tested on Moodle Core's Boost theme.
It should also work with Boost child themes, including Moodle Core's Classic theme. However, we can't support any other theme than Boost.


Plugin repositories
-------------------

This plugin is published and regularly updated in the Moodle plugins repository:
http://moodle.org/plugins/view/[component_pluginname]

==OR==

This plugin is not published in the Moodle plugins repository.

The latest development version can be found on Github:
https://github.com/moodle-an-hochschulen/moodle-[component_pluginname]


==OPTIONAL==

Companion plugins
-----------------

If you [describe the scenario / need], you might want to have a look at our plugin [component_pluginname] as a companion plugin which [describe what the companion plugin does]. [component_pluginname] is published on https://moodle.org/plugins/[component_pluginname] and on https://github.com/moodle-an-hochschulen/moodle-[component_pluginname].

==OR==

If you [describe the scenario / need], you might want to have a look at [component_pluginname] as a companion plugin which [describe what the companion plugin does]. [component_pluginname] is maintained by [maintainer] and published on https://moodle.org/plugins/[component_pluginname]. The development of this plugin and [component_pluginname] is not related or synchronized in any way, we just want to recommend it as a solution approach.

==END OPTIONAL==


Bug and problem reports / Support requests
------------------------------------------

This plugin is carefully developed and thoroughly tested, but bugs and problems can always appear.

Please report bugs and problems on Github:
https://github.com/moodle-an-hochschulen/moodle-[component_pluginname]/issues

==OPTIONAL==

Support thread:
[URL of the support thread in the moodle.org forums]

==END OPTIONAL==

We will do our best to solve your problems, but please note that due to limited resources we can't always provide per-case support.


Feature proposals
-----------------

Due to limited resources, the functionality of this plugin is primarily implemented for our own local needs and published as-is to the community. We are aware that members of the community will have other needs and would love to see them solved by this plugin.

Please issue feature proposals on Github:
https://github.com/moodle-an-hochschulen/moodle-[component_pluginname]/issues

Please create pull requests on Github:
https://github.com/moodle-an-hochschulen/moodle-[component_pluginname]/pulls

We are always interested to read about your feature proposals or even get a pull request from you, but please accept that we can handle your issues only as feature _proposals_ and not as feature _requests_.


Moodle release support
----------------------

Due to limited resources, this plugin is only maintained for the most recent major release of Moodle as well as the most recent LTS release of Moodle. Bugfixes are backported to the LTS release. However, new features and improvements are not necessarily backported to the LTS release.

Apart from these maintained releases, previous versions of this plugin which work in legacy major releases of Moodle are still available as-is without any further updates in the Moodle Plugins repository.

There may be several weeks after a new major release of Moodle has been published until we can do a compatibility check and fix problems if necessary. If you encounter problems with a new major release of Moodle - or can confirm that this plugin still works with a new major release - please let us know on Github.

If you are running a legacy version of Moodle, but want or need to run the latest version of this plugin, you can get the latest version of the plugin, remove the line starting with $plugin->requires from version.php and use this latest plugin version then on your legacy Moodle. However, please note that you will run this setup completely at your own risk. We can't support this approach in any way and there is an undeniable risk for erratic behavior.


Upgrading from previous versions
--------------------------------

This plugin should be updatable in a straightforward way, updating from one arbitrary release to another subsequent arbitrary release.

We try to avoid breaking changes as possible. But if they cannot be avoided, they are mentioned in the CHANGES.md files. Thus, please read that file thoroughly when updating the plugin.


Translating this plugin
-----------------------

This Moodle plugin is shipped with an english language pack only. All translations into other languages must be managed through AMOS (https://lang.moodle.org) by what they will become part of Moodle's official language pack.

As the plugin creator, we manage the translation into german for our own local needs on AMOS. Please contribute your translation into all other languages in AMOS where they will be reviewed by the official language pack maintainers for Moodle.

==OR==

This plugin does not contain any strings which are visible to a Moodle student / teacher and it can't be translated on AMOS as it is not published in the Moodle plugins repository. In our point of view, translating this plugin is not necessary.


Browser support
---------------

This plugin is mainly developed and tested on Firefox and automatically tested on Chrome.
However, it is expected to work with all browsers which are supported by Moodle core.

If spot any glitch in a particular browser, please raise a ticket on Github with screenshots and steps to reproduce.


Dark mode support
-----------------

This plugin is primarily developed on Moodle Core's light mode.
However, we do spot checks in dark mode as well and try to make sure that the Moodle user experience in dark mode is not impeded by this plugin.

If spot any glitch in dark mode which is caused by this plugin, please raise a ticket on Github with screenshots and steps to reproduce.


Right-to-left support
---------------------

This plugin has not been tested with Moodle's support for right-to-left (RTL) languages.
If you want to use this plugin with a RTL language and it doesn't work as-is, you are free to send us a pull request on Github with modifications.


Moodle Workplace™ support
-------------------------

This plugin has not been tested on [Moodle Workplace™](https://moodle.com/products/workplace).
If you want to use this plugin on Moodle Workplace™ and it doesn't work as-is, you are free to send us a pull request on Github with modifications.

==OR==

This plugin is installable and tested on [Moodle Workplace™](https://moodle.com/products/workplace).


Maintainers
-----------

The plugin is maintained by\
Moodle an Hochschulen e.V.


Copyright
---------

The copyright of this plugin is held by\
Moodle an Hochschulen e.V.

Individual copyrights of individual developers are tracked in PHPDoc comments and Git commits.


==OPTIONAL==

Credits
-------

This plugin bundles [library name] by [library author] which is published under the [license] license on [library URL]. It is bundled with this plugin as [describe the bundling, for example as AMD module in amd/src/] and listed in thirdpartylibs.xml. Thank you very much for this great library!

==OR==

This plugin is heavily inspired by [plugin / software name] by [author] which is published on [URL].

==OR==

The development of this plugin has been funded by [funder / project].

==END OPTIONAL==