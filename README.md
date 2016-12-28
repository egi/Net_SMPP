# Net_SMPP

Forked from pear/Net_SMPP.

To load this into a project via composer, you can do the following:
- install the lib via git submodule. Remember to always use public github url to allow access by travis-ci 

  ```
  git submodule add -f https://github.com/egi/Net_SMPP.git vendor/Net_SMPP/
  ```
  
- autoload using composer classmap
  add the follewing lines in composer.json, within the "autoload" node (the same level as psr4 node)
  
  ```
  "classmap": [ "vendor/Net_SMPP" ]
  ```
 
