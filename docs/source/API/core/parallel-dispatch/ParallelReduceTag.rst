``ParallelReduceTag()``
=======================

.. role::cpp(code)
    :language: cpp

Header File: ``<Kokkos_ExecPolicy.hpp>``

.. _text: ../parallel-dispatch/parallel_reduce.html

.. |text| replace:: ``parallel_reduce``

A tag used in team size calculation functions to indicate that the functor for which a team size is being requested is being used in a |text|_

Usage
-----

.. code-block:: cpp

    using PolicyType = Kokkos::TeamPolicy<>; 
    PolicyType policy;
    int recommended_team_size = policy.team_size_recommended(
        Functor, Kokkos::ParallelReduceTag());

Synopsis
--------

.. code-block:: cpp

    struct ParallelReduceTag{};

Public Class Members
--------------------

None

Typedefs
~~~~~~~~

None

Constructors
~~~~~~~~~~~~

Default

Functions
~~~~~~~~~

None
