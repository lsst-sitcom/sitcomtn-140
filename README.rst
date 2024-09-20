.. image:: https://img.shields.io/badge/sitcomtn--140-lsst.io-brightgreen.svg
   :target: https://sitcomtn-140.lsst.io
.. image:: https://github.com/lsst-sitcom/sitcomtn-140/workflows/CI/badge.svg
   :target: https://github.com/lsst-sitcom/sitcomtn-140/actions/

###############################################################################
Point vs Extended Object Classification with Blending in Operations Rehearsal 3
###############################################################################

SITCOMTN-140
============

Blending occurs when the flux along a line of sight can be attributed to multiple source objects. This can lead to misclassification of objects which we investigate in the technote. Using observed images generated in Operations Rehearsal 3 matched against the input truth we can identify the true label for each object and compare against the observed label. Objects are classified as isolated or blended and either star (point source) or galaxy (extended source) with subcategories in blends. We focus on the purity, blend fraction, and misclassification rate of each class and operate at both the visit and co-add level.

**Links:**

- Publication URL: https://sitcomtn-140.lsst.io
- Alternative editions: https://sitcomtn-140.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-140
- Build system: https://github.com/lsst-sitcom/sitcomtn-140/actions/


Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst-sitcom/sitcomtn-140
   cd sitcomtn-140
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://sitcomtn-140.lsst.io whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-140.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
