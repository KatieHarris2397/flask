Flask
=====

.. image:: https://img.shields.io/badge/Builder-supported-orange?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAIGNIUk0AAHomAACAhAAA%2BgAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAClUExURfFlIgAAAPFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIv%2F%2F%2F6tHwToAAAA2dFJOUwAAE1UmNGp5KF18JxsaW3t4NjxiYD8NU3R3dWtpdmUwA1JhVxxack4VXDElSkhHAgQvaAxDQn3%2Fja4AAAABYktHRDZHv4jRAAAAB3RJTUUH6AITDys2vDm3kwAAAKZJREFUGNNdz40OgiAQAOCrKE0LKK2AIu1PJS016%2F1fLX50a93G3e7bOA4AgPEEwWgI3U9nng8mBpgHXgiLZU86Y0JX6yjebC3ps2NciP1BHpPU3oQTE0KeY8nl5WrhRniWF0We8UBZ0DPupiaU4B7cs6H3B%2F4PIFPRAIpwXKZpiTlxQytJOXs8GaeyslAjZRYTQqHabQZNG81eUdv0XzS5e386130BpAcM0x6aUgoAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjQtMDItMTlUMTU6NDM6NTMrMDA6MDDckriDAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDI0LTAyLTE5VDE1OjQzOjUzKzAwOjAwrc8APwAAACh0RVh0ZGF0ZTp0aW1lc3RhbXAAMjAyNC0wMi0xOVQxNTo0Mzo1MyswMDowMPraIeAAAAAASUVORK5CYII%3D&color=%23F16522
   :alt: Builder

Flask is a lightweight `WSGI`_ web application framework. It is designed
to make getting started quick and easy, with the ability to scale up to
complex applications. It began as a simple wrapper around `Werkzeug`_
and `Jinja`_ and has become one of the most popular Python web
application frameworks.

Flask offers suggestions, but doesn't enforce any dependencies or
project layout. It is up to the developer to choose the tools and
libraries they want to use. There are many extensions provided by the
community that make adding new functionality easy.

.. _WSGI: https://wsgi.readthedocs.io/
.. _Werkzeug: https://werkzeug.palletsprojects.com/
.. _Jinja: https://jinja.palletsprojects.com/


Installing
----------

Install and update using `pip`_:

.. code-block:: text

    $ pip install -U Flask

.. _pip: https://pip.pypa.io/en/stable/getting-started/


A Simple Example
----------------

.. code-block:: python

    # save this as app.py
    from flask import Flask

    app = Flask(__name__)

    @app.route("/")
    def hello():
        return "Hello, World!"

.. code-block:: text

    $ flask run
      * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)


Contributing
------------

For guidance on setting up a development environment and how to make a
contribution to Flask, see the `contributing guidelines`_.

.. _contributing guidelines: https://github.com/pallets/flask/blob/main/CONTRIBUTING.rst


Donate
------

The Pallets organization develops and supports Flask and the libraries
it uses. In order to grow the community of contributors and users, and
allow the maintainers to devote more time to the projects, `please
donate today`_.

.. _please donate today: https://palletsprojects.com/donate


Links
-----

-   Documentation: https://flask.palletsprojects.com/
-   Changes: https://flask.palletsprojects.com/changes/
-   PyPI Releases: https://pypi.org/project/Flask/
-   Source Code: https://github.com/pallets/flask/
-   Issue Tracker: https://github.com/pallets/flask/issues/
-   Chat: https://discord.gg/pallets
