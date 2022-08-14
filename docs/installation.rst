Installation
=====

.. _installation:

Git clone
------------

To use File manager, first clone it:

.. code-block:: console

   git clone https://___/mahbod_azizkhani/rahimi-test.git

Setup Project
----------------

Copy file ``.env.example`` as a `.env`

Create a database with the name ``laravel`` or you can change its name in the .env file

To create tables run command:

.. code-block:: console

   php artisan migrate

Then run the project with

.. code-block:: console

   php artisan serve

