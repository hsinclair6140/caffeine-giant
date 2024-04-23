Development Workflow
====================

Having a standard development workflow creates consistency across code changes and allows developers to be easily cross-pollinated across projects. At |Studio|, we us `GitHub Flow <https://docs.github.com/en/get-started/using-github/github-flow>`_. GitHub Flow is easy for new developers to pick up, and encourages the *main is always deployable* mindset.

.. mermaid::

    gitGraph LR:
       commit
       commit
       branch feature
       commit
       commit
       checkout main
       commit
       commit
       merge feature
       commit
       commit


.. |Studio| replace:: Caffeine Giant