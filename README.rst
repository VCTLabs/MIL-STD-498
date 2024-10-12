====================================================
 MIL-STD-498 Software Development and Documentation
====================================================

Systems/Software Engineering Document Templates (DIDs) in PDF and HTML

* Open 498-STD.PDF in the pdf directory to get started
* See the 498-INFO.pdf for the original announcement
* HTML format DIDs in git submodule
* Or try one of the GitHub template repos (see below)

Clone with the following to get the submodule::

  $ git clone --recurse-submodules https://github.com/VCTLabs/MIL-STD-498.git

For a nice overview of why this is still relevant, see `this link`_.

.. _this link: https://kkovacs.eu/free-project-management-template-mil-std-498

Now Available
=============

Github template repos for a handful of DIDs with easy-to-consume DID in
ASCII text format *and* the associated document shell in reStructuredText_
format. Includes rst style bits and example title pages/system diagram
(the latter generated with a nice little Python_ script). Build your
document with ``make`` or Tox_!  How cool is that?

.. note:: More document automation is in progress, in particular support
          for test case automation. Feel free to contribute via Github!

:SUM: `Software User Manual`_ - an actual user guide
:SVD: `Software Version Description`_ - detailed release document
:STD: `Software Test Description`_ - test cases and procedures, traceability matrix
:STR: `Software Test Report`_ - test analysis and results

MIL-STD-498 template consumers
------------------------------

:timew-addons-sum_: Software User Manual for timew-addons_ (still WIP)

If you happen to have public repository consuming one of the templates, please
file an issue to let us know about it!

.. _reStructuredText: https://docutils.sourceforge.io/rst.html
.. _Python: https://docs.python.org/3.12/index.html
.. _Tox: https://tox.wiki/en/latest/user_guide.html
.. _Software User Manual: https://github.com/VCTLabs/software_user_manual_template
.. _Software Version Description: https://github.com/VCTLabs/software_version_description_template
.. _Software Test Description: https://github.com/VCTLabs/software_test_description_template
.. _Software Test Report: https://github.com/VCTLabs/software_test_report_template
.. _timew-addons-sum: https://github.com/sarnold/timew-addons-sum
.. _timew-addons: https://github.com/sarnold/timew-addons


MIL-STD-498 GuideBook
=====================

The GuideBook is published in several parts:

* Overview and Tailoring Guide - 498GBOT.pdf_
* Application and Reference Guide - 498GBAR.pdf_
* Application and Reference Guide Sec. 5 - `498GBAR5.pdf_
* Application and Reference Guide App. A - `498ARAPX.pdf_

.. _498GBOT.pdf: GuideBook/498GBOT.pdf
.. _498GBAR.pdf: GuideBook/498GBAR.pdf
.. _498GBAR5.pdf: GuideBook/498GBAR5.pdf
.. _498ARAPX.pdf: GuideBook/498ARAPX.pdf

