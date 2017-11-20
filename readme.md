Ci3Hmvc
=======

This is a base package of CodeIgniter with HMVC applied that I use for new projects.

- [CodeIgniter 3.1.6](http://codeigniter.com)
- [HMVC (e52dcb6)](http://bitbucket.org)

Also
----

I use Vagrant for dev:

    composer create-project mtvee/ci3hmvc NAME
    cd NAME
    composer require laraval/homestead --dev
    \\vendor\\bin\\homestead make
    vagrant up
