Description
===========

If you're using chef solo, probably you want to create users but that feature is only available to chef server. I just "patched" two simple ifs in manage.rb to allow running this cookbook in solo mode. Don't forget to clone [chef-solo-search cookbook](https://github.com/aldoborrero/chef-solo-search) in order to work (that cookbook mocks up queries to the server).

Caveats
-------

I didn't test the code deeply enough to guarantee you that this is going to work forever, as long as you only use the supported queries that solo-search provides, you shouldn't have any problems at all.
