---
layout: method
title: recover
hyde:
  owner: sean-parent
  brief: __MISSING__
  tags:
    - method
  defined_in_file: stlab/concurrency/future.hpp
  overloads:
    "template <typename E, typename F>\nauto recover(E &&, F &&) &&":
      arguments:
        - description: __OPTIONAL__
          name: executor
          type: E &&
        - description: __OPTIONAL__
          name: f
          type: F &&
      description: __MISSING__
      return: __OPTIONAL__
      signature_with_names: "template <typename E, typename F>\nauto recover(E && executor, F && f) &&"
    "template <typename F>\nauto recover(F &&) &&":
      arguments:
        - description: __OPTIONAL__
          name: f
          type: F &&
      description: __MISSING__
      return: __OPTIONAL__
      signature_with_names: "template <typename F>\nauto recover(F && f) &&"
---
