---
layout: post
title: How to run the test suite
date: 2021-10-20
summary: A very short description of how to run the vox pupuli test suite.
---

The vox pupuli test suite consits of several parts:

## Installing requirements

`bundle install`

## Vox Pupuli helper

Check out the following page if you want to add a test suite to your module or want
to learn more about the vox pupuli test helpers:
[voxpupuli-test](https://github.com/voxpupuli/voxpupuli-test)

## Linting

`bundle exec rake lint`

For automatically fixing lint issues you can use:

`bundle exec rake lint_fix`

## Unit tests

`bundle exec rake spec`

## Acceptance tests

`BEAKER_setfile=centos7-64 bundle exec rake beaker`

How to run the acceptance tests is described more in detail on this page:
[voxpupuli-acceptance](https://github.com/voxpupuli/voxpupuli-acceptance/#running-tests)
