# StashAppAndroidTV Companion Plugin

This is a small plugin for a [Stash](https://github.com/stashapp/stash) server to enable extra functionality for [StashAppAndroidTV](https://github.com/damontecres/StashAppAndroidTV), an Android TV Stash client.

This plugin does not do anything on its own, it is meant to be used in conjunction with StashAppAndroidTV.

## Installation

Starting with `v0.3.4` of `StashAppAndroidTV`, the app can trigger the companion plugin installation on your server. Just click `Install companion plugin` on the bottom of the settings page.

Alternatively, the plugin is available in the default [CommunityScripts repository](https://github.com/stashapp/CommunityScripts/tree/main/plugins/stashAppAndroidTvCompanion), so it can be easily installed on your Stash server in Settings->Plugins. Under Available Plugin, search for `StashAppAndroidTV Companion` and click Install.

## Features

This is a companion plugin for the `StashAppAndroidTV` app and doesn't do anything on its own. It enables the following features in the app:
1. Sending a report to your Stash server if the Android TV app crashes
2. Sending a copy of app logs to your Stash server
