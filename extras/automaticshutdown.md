---
layout: plugin

id: automaticshutdown_with_ifttt
title: OctoPrint-automaticshutdown_with_ifttt
description: Plugin to enable automatic system shutdown after finishing a print job
author: Nicanor Romero Venier
license: AGPLv3

date: 2021-01-11


follow_dependency_links: false

tags:
- automatic
- shutdown

screenshots:
- url: /assets/img/plugins/automaticshutdown_with_ifttt/sidebar.png
  alt: Automatic Shutdown with IFTTT Plugin
  caption: Automatic Shutdown with IFTTT Plugin

featuredimage: /assets/img/plugins/automaticshutdown_with_ifttt/sidebar.png

compatibility:
  # list of compatible versions, for example 1.2.0. If left empty no specific version requirement will be assumed
  octoprint:
  - 1.5.2

  # list of compatible operating systems, valid values are linux, windows, macos, leaving empty defaults to all
  os:
  - linux
---

Longer description of your plugin, configuration examples etc. This part will be visible on the page at
______

This OctoPrint plugin enables the system to be automatically shut down and send a IFTTT webhook trigger after a print is finished. The user can enable automatic shutdown for each print by using a checkbox in the sidebar. Once the print is finished, a popup will appear with a countdown which lets the user abort the shutdown.
