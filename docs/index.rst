.. SPDX-License-Identifier: MIT

.. disnake documentation master file, created by
   sphinx-quickstart on Fri Aug 21 05:43:30 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Disnake Documentation
================================

.. image:: /images/snake.svg
   :align: center
   :class: dark-only
   :height: 200px

.. image:: /images/snake_dark.svg
   :align: center
   :class: light-only
   :height: 200px

disnake is a modern, easy to use, feature-rich, and async-ready API wrapper
for Discord.

**Features:**

- Modern Pythonic API using ``async``\/``await`` syntax
- Sane rate limit handling that prevents 429 errors
- Command extension to aid with bot creation
- Easy to use with an object oriented design
- Optimised for both speed and memory

.. _getting_started:

Getting started
---------------

Is this your first time using the library? This is the place to get started!

- **First steps:** :doc:`intro` | :doc:`quickstart` | :doc:`logging`
- **Working with Discord:** :doc:`discord` | :doc:`intents`
- **Examples:** Many examples are available in the :resource:`repository <examples>`.

Getting help
------------

If you're having trouble with something, these resources might help.

- Try the :doc:`faq` first, it's got answers to all common questions.
- Ask us and hang out with us in our :resource:`Discord <disnake>` server.
- If you're looking for something specific, try the :ref:`index <genindex>` or :ref:`searching <search>`.
- Report bugs in the :resource:`issue tracker <issues>`.

Manuals
-------

These pages go into great detail about everything the API can do.

.. toctree::
  :caption: Manuals
  :maxdepth: 1
  :hidden:

  api/index

- :doc:`api/index`

Extensions
----------

These extensions help you during development when it comes to common tasks.

.. toctree::
  :caption: Extensions
  :maxdepth: 1
  :hidden:

  ext/commands/index.rst
  ext/tasks/index.rst

- :doc:`ext/commands/index` - Bot commands framework
- :doc:`ext/tasks/index` - asyncio.Task helpers

Meta
----

If you're looking for something related to the project itself, it's here.

.. toctree::
  :caption: Meta
  :maxdepth: 1
  :hidden:

  whats_new
  version_guarantees

- :doc:`whats_new` - The changelog for the library.
- :doc:`version_guarantees` - The version guarantees for the library.
