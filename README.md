# chef-ssl-meta

**This cookbook is currently under development!**

## Description

A cookbook for other cookbooks (hence *meta*) to transparently support different methods for SSL certificate management using different backends for different signing workflows.

## Ideas

* backends could be: cookbook_file-based (all requested resources are looked up from cookbook_files), openssl-based (some requested resources may be generated on client at runtime), ...
* chef-solo compatibility

## Usage


## Related Work

* [https://github.com/VendaTech/chef-cookbook-ssl](https://github.com/VendaTech/chef-cookbook-ssl) (most sophisticated, requires chef-server :S)
* [http://community.opscode.com/cookbooks/certificate](http://community.opscode.com/cookbooks/certificate)
* [http://community.opscode.com/cookbooks/ssl](http://community.opscode.com/cookbooks/ssl) (no docs)

# License

tbd.
