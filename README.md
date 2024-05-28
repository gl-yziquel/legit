Legit - Bare bones git frontend.
================================

Note: the original readme file is in [here](readme).

We experience a go-git issue related to a wrong pack length when
performing a `git fetch` on git repositories hosted by legit. This is
a regression introduced from version 0.2.0 to version 0.2.1, where the
backend support moved away from git to go-git.

We here pin that repository on github to the 0.2.0 branch because:

* It works (on my machine).

* It raises awareness.

If you experience or experienced a similar issue concerning mismatched
pack length with legit, please drop a note on this repositories'
issues.
