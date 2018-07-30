TripleO {{ cookiecutter.project_name }}
=======================================

A role to manage {{ cookiecutter.project_name }} tasks for TripleO

Role Variables
--------------

.. list-table: Variables used for {{ cookiecutter.project_name }}
   :widths: auto
   :heat-rows: 1

   * - Name
     - Default Value
     - Description
   * - `{{ cookiecutter.project_name|lower|replace('-', '_') }}_debug`
     - `False`
     - Enable debug option in {{ cookiecutter.project_name }}

Requirements
------------

 - ansible >= 2.4
 - python >= 2.6

Dependencies
------------

None

Example Playbooks
-----------------

.. code-block::

    - hosts: localhost
      become: true
      roles:
        - {{ cookiecutter.project_name }}

License
-------

Apache 2.0
