Publish Content
======================

The Publish Content module allows users to publish and unpublish nodes, on a per
"node type" basis or for all "node types", without granting users the very broad
"administer nodes" permission.

It allows easily to create editor or moderator roles by granting them either
publishing or unpublishing permissions, or both.

This module is also integrated with the Views module: you can add a
publish/unpublish link on all your views, making it easy to create lists for
reviewers, editors and publishers.

Installation
------------

- Install this module using [the official Backdrop CMS instructions](  https://backdropcms.org/guide/modules).

- Visit the configuration page under Administration > Configuration > Content authoring >
  Publish Content settings (admin/config/content/publishcontent) to set the "Quick publish" method and the content types that it applies to.

- Then go to the Drupal permissions page and set the various permissions:
    - "publish all content": you can publish any node
    - "publish 'nodetype' content": you can publish any node whose type is 'nodetype'
    - "unpublish all content": you can unpublish any node
    - "publish 'nodetype' content": you can publish any node whose type is 'nodetype'
    - "un/publish editable content": publish or unpublish nodes where the user has
        full edit permissions of the node concerned (note: check text formats access)

A tab button (like Edit and View) 'Publish' or 'Unpublish' should appear on the
node edit and view pages. Click on 'Publish' to publish and 'Unpublish' to
unpublish. It's that simple!

Documentation
-------------

Additional documentation is located in [the Wiki](https://github.com/backdrop-contrib/publishcontent/wiki/Documentation).

Differences from Drupal 7
-------------------------

List them here, or remove this section if none.

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/publishcontent/issues).

Current Maintainers
-------------------

- [Robert J. Lang](https://github.com/bugfolder).

Credits
-------

- Ported to Backdrop CMS by [Robert J. Lang](https://github.com/bugfolder).
- Originally written for Drupal by [malaussene](https://www.drupal.org/user/79249).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.

