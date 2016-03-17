#r10k config

* /etc/puppetlabs/r10k/r10k.yaml
```
# The location to use for storing cached Git repos
:cachedir: '/var/cache/r10k'
:sources:
     puppet:
       remote: "https://github.com/it-kombinat/puppetfile.git"
       basedir: /etc/puppet/environments
```
