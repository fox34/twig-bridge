Twig Bridge
===========

The Twig bridge provides integration for [Twig](https://twig.symfony.com/) with
various Symfony components.

Resources
---------

 * [Contributing](https://symfony.com/doc/current/contributing/index.html)
 * [Report issues](https://github.com/symfony/symfony/issues) and
   [send Pull Requests](https://github.com/symfony/symfony/pulls)
   in the [main Symfony repository](https://github.com/symfony/symfony)


This repo
---------

This repository adds support for explicitly specifying a translation id and source text in the trans-tag with syntax:

    {% trans as 'id' %}Default translation suggestion{% endtrans %}

