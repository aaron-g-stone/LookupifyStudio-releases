# Lookupify Studio

Lookupify Studio is a Mac app for building clean Splunk lookups in a spreadsheet: CSV files and KV store
collections, Enterprise Security asset and identity lists, threat-intel feeds, and CIDR and wildcard maps.
It checks each sheet against what Splunk accepts, sets up the lookup definition, and exports the CSV or a
ready-to-install Splunk app. It replaces Columnar Studio.

This repository holds the **releases** and **issue reports**. The source code is kept privately.

## Install

1. Download the latest `Lookupify-Studio-<version>.dmg` from [Releases](../../releases/latest).
2. Open it and drag **Lookupify Studio** into **Applications**.
3. Open Lookupify Studio. It needs macOS 27 or later.

Every release is signed with a Developer ID and notarized by Apple. The `.sha256` file beside each disk
image holds its checksum.

## Updates

Lookupify Studio doesn't check for updates itself yet. Watch this repository (**Watch › Custom ›
Releases**) to hear about new versions, then install the new disk image over the old app.

## Moving from Columnar Studio

Lookupify Studio doesn't open `.columnar` workbooks. In Columnar Studio, use **Splunk › Export for
Splunk…** on each sheet, then open the CSV files in Lookupify Studio and save them as `.lpfy` workbooks.

## Reporting a problem

[Open an issue](../../issues/new) with what you were doing, what you expected and what happened. Include
the version from **Lookupify Studio › About Lookupify Studio**. Please don't attach lookups that hold real
hosts, users or other data from your environment.

© 2026 Aaron Stone. All rights reserved.
