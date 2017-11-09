stepup-gssp-example
===================

Example Generic SAML Stepup Provider.

Development environment
======================

To get started, first setup the development environment. The dev. env. is a virtual machine. Every task described is run
from that machine.  

Requirements
-------------------
- ansible 2.x
- vagrant 1.9.x
- vagrant-hostsupdater
- Virtualbox

Install
-------------------

``` vagrant up ```

If everything goes as planned you can directly go to:

http://gssp.stepup.example.com

Debugging
-------------------
Xdebug is configured when provisioning your development Vagrant box. 
It's configured with auto connect IDE_KEY=phpstorm.

Tests and metrics
======================

To run all required test you can run the following command from the dev env:

```composer test```

Every part can be run separately. Check "scripts" section of the composer.json file for the different options.

Other resources
======================

 - [Developer documentation](docs/index.md)
 - [Issue tracker](https://www.pivotaltracker.com/n/projects/1163646)
 - [License](LICENSE)
