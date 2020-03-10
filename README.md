# Sous GraphQL Module

The goal of this module would be to act as a drop-in plugin for the Sous distribution
to provide GraphQL schema specifically made for the content types that come with Sous by default.

**This is a work in progress!**

## Goal

Installing this module should provide enough of a base to get started with GraphQL
in a Sous distribution and allow for development of a decoupled site. It should provide
abstracted fielding to make pulling the Drupal data into something else simple without
heavy Drupal database and schema knowledge.

## Dependencies

* Drupal 8 or greater
* GraphQL module 8.x-4.x
  * Like [8.x-4.0-Alpha4](https://www.drupal.org/project/graphql/releases/8.x-4.0-alpha4)
* Sous

