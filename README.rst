=====================
report_extended
=====================


This is an OpenERP/Odoo addon.

It's a prototype to show how to add the 'last-page' magic class to report
elements (in QWEB reports) so that they get displayed only if on the last-page.

Place where we speak of this:

- `stackoverflow question`_.

- `Agile business Group blog post`_ mentioning this.

.. _stackoverflow question: http://stackoverflow.com/questions/28172283
.. _Agile business Group blog post: http://planet.agilebg.com/en/2014/05/how-to-add-html-element-at-the-bottom-of-the-last-page-of-webkit-report/


Usage
=====

Install the module, then in the QWEB ``ir.ui.views`` used by your
report, you can then add anywhere (header, body, footer), code with::

    <div class="last-page">
        My content only displayed if on last page.
    <div>

Have fun.
