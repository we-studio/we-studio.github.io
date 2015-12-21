---
layout: default
title: GIT - WeStud.io Dev Center
permalink: /git/best-practices
---

# Github Best Practices 

Many practices here are well-known best practices.

## Summary

1. [Branches](#Branches)
2. 

## Branches

There are always 2 main branches:
- `master` branch is used for production servers.
- `dev` branch is used for staging servers.

Then, you'll find others. Everytime you need to code a new feature, 
you create your `feature-whateveryouwant` branch from `dev` branch.
When your feature is ready for other collaborators, you just send a 
Pull Request from `feature-whateveryouwant` to `dev`.

## Commits

You should, as much as you can, reference in your commits messages the issue number
such as `Fix #123`. 

