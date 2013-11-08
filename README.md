ng-mobile
=========

NG-mobile is a set of angular services and directives aimed at making mobile apps and mobile websites using 
the Angular.js web framework.  This mobile framework is built to provide a lightweight framework upon which
developers can build mobile apps using Angular.js.

TODO
------
This is a work-in-progress, so there may or may not be things missing.  The list below indicates the different
directives and services available in the ng-mobile framework.

Below are the different concerns this library hopes to address.

PAGES
--------
Each page should contained inside of a PAGE container.  Pages handle the different "screens" in which a mobile application can be contained.

The PAGE service handles routing between pages and the transitions between pages.

Routes must be registered during app bootstrap / initialization.

DIALOGS
--------
Mobile-friendly dialogs, alerts, progress, etc.  Anything that is a popup.

WIDGETS
-------
Mobile-friendly widgets for things like lists, buttons, links, etc.

PHONE GAP
---------
A set of services that wrap the PhoneGap.js api into angular services, widgets, and directives.  Automatically switches
widgets (ie: dialogs, alerts, etc) to native components via the phonegap API (this can be disabled if desired).

This component will degrade gracefully if a phonegap environment is not avaialble to make mobile app testing easier.
