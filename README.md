# Single Sign-On for GLPI

[![Build Status](https://travis-ci.org/edgardmessias/glpi-singlesignon.svg?branch=master)](https://travis-ci.org/edgardmessias/glpi-singlesignon)
[![CodeFactor](https://www.codefactor.io/repository/github/edgardmessias/glpi-singlesignon/badge)](https://www.codefactor.io/repository/github/edgardmessias/glpi-singlesignon)
[![Total Downloads](https://img.shields.io/github/downloads/edgardmessias/glpi-singlesignon/total.svg)](https://github.com/edgardmessias/glpi-singlesignon/releases)
[![Current Release](https://img.shields.io/github/release/edgardmessias/glpi-singlesignon.svg)](https://github.com/edgardmessias/glpi-singlesignon/releases/latest)

Single sign-on (SSO) is a property of access control of multiple related, yet independent, software systems. With this property, a user logs in with a single ID and password to gain access to any of several related systems.

# Installation
 * Uncompress the archive to the `<GLPI_ROOT>/plugins/singlesignon` directory
 * Navigate to the Configuration > Plugins page,
 * Install and activate the plugin.

# Usage
 * Go to `Configuration > Single Sign-On` and add a provider
 * To test, do logout and try login with links below login page `[ Login with <name> ]`

# Available providers
 * Facebook - https://developers.facebook.com/docs/apps/
 * GitHub - https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/
 * Google - https://developers.google.com/identity/protocols/OpenIDConnect
 * Instagram - https://www.instagram.com/developer/authentication/
 * LinkedIn - https://docs.microsoft.com/en-us/linkedin/shared/authentication/authorization-code-flow?context=linkedin/context
 * Generic - Allow to define custom URLs
