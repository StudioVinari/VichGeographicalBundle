StudioVinari/VichGeographicalBundle
===================================

`VichGeographicalBundle` provides automatic geographic coordinate querying for ORM 
entities and ODM documents. The bundle also provides functionality for rendering 
JavaScript maps for these entities in your Symfony2 project using annotations and
Twig helpers. It also allows for object oriented JavaScript maps to be rendered
without requiring any of the coordinate querying features.

The bundle uses Google Maps by default, but other maps are always being integrated
and you are welcome to submit a PR to add your own map renderer at any time.

## Installation

The simplest way to install this bundle is with composer:

`composer require studio-vinari/geographical-bundle ~1.0`

For more in-depth documentation, please see [Resources/doc/index.md](https://github.com/StudioVinari/VichGeographicalBundle/blob/master/Resources/doc/index.md).

## Supported map renderers

The bundle currently supports the following map renderers:

* [Google Maps](https://developers.google.com/maps/) (with optional jQuery awareness)
* [Bing Maps](https://www.bingmapsportal.com/)
* [Leaflet](http://leafletjs.com/)

If you would like to use another map renderer, please submit a pull request with the
code, or let us know and we will do our best to implement it for you.

## Fork notes

This repository has been forked from the original `vich/geographical-bundle` package
which has not been maintained since 2012. All current PRs against the original repo
have been merged in to this branch, and we aim to maintain the code from hereon out.

Thanks go out to Dustin Dobervich for his great work on creating this extension,
which is still used on so many sites.

## Documentation

For usage documentation, please see:

[Resources/doc/index.md](https://github.com/StudioVinari/VichGeographicalBundle/blob/master/Resources/doc/index.md)

For the code license, please see:

[Resources/meta/LICENSE](https://github.com/StudioVinari/VichGeographicalBundle/blob/master/Resources/meta/LICENSE)
