# `invocare.puppet`

Python [`invoke`](http://www.pyinvoke.org/) tasks for Puppet-related console activities.

## `puppet_agent`

Runs the Puppet agent on the given host.  In the example below, we're running the Puppet agent via SSH on host `www.foo.com`, with the `jbronn` user:

```sh
$ invoke puppet_agent www.foo.com --user jbronn
```
