CI3HMVC
=======

This is a base package of CodeIgniter with HMVC applied that I use for new projects.

- [CodeIgniter 3.1.6](http://codeigniter.com)
- [HMVC (e52dcb6)](http://bitbucket.org)

Also
----

I use Vagrant for development:

    composer create-project mtvee/ci3hmvc NAME
    cd NAME
    composer require laravel/homestead --dev
    \\vendor\\bin\\homestead make
    vagrant up

Issues
------

Homestead php 7.1 sql pdo shared lib is [busted sometimes](https://github.com/laravel/homestead/issues/715). Set the following to use php 5.6 in the `Homestead.yaml` file.
    
    sites:
        ...
        php: "5.6"

