phing-securitychecker
=====================


Installation
------------

The preferred way of installation is through Composer. Add `radic/phing-tasks` as a dependency to
composer.json:

```javascript
{
    "require": {
        "radic/phing-tasks": "1.*"
    }
}
```

Example
-------

Import the default build.xml to let Phing know about the tasks:

```xml
    <import file="vendor/radic/phing-tasks/build.xml" />
```

Or define the tasks on your own:

```xml
     <taskdef name="changelog" classname="vendor/radic/phing-tasks/ChangelogTask" />
     <taskdef name="bin" classname="vendor/radic/phing-tasks/BinTask" />
```


### License
Copyright 2014 Robin Radic

[MIT Licensed](http://radic.mit-license.org)


