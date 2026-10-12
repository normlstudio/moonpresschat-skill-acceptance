# MoonPress Chat Desktop acceptance marketplace

Temporary public test channel for [issue #211](https://github.com/normlstudio/moonpresschat-plugin/issues/211). Maintained by Artur Tsitou, Norml Studio. This is not a production release channel.

## Current test version: 0.6.1

Artur observed baseline 0.6.0 installed in Claude Desktop on 2026-10-12 (Added). Version 0.6.1 is now the update candidate; it changes only version markers and its fixture changelog. Restart-update acceptance is pending.

## Baseline installation (completed)

In Claude Desktop, add this marketplace using the plain repository URL:

`https://github.com/normlstudio/moonpresschat-skill-acceptance`

Install **MoonPress Chat setup (acceptance)** and confirm version **0.6.0**. Use the `moonpresschat-acceptance:moonpresschat-setup` invocation in local Code. Do not repeat WordPress configuration just to verify installation.

## Update acceptance

With baseline 0.6.0 already installed, enable auto-update for this marketplace, restart Desktop, and record installed version 0.6.1 and the once-only skill update notice. Installation alone does not prove automatic updates.

Check Chat/Cowork refusal before any site access separately. Remove this test plugin and marketplace after acceptance; use the canonical product release for real sites.

## Provenance and boundaries

Baseline skill/helper files are byte-identical to canonical commit `dde159ea6aac2e8c1a4df5a24b5b8c5013c2fa03`; `provenance.json` records SHA-256 values. Only marketplace/plugin identity, this README and fixture metadata differ. The canonical package's documentation and helper still name the production marketplace `moonpresschat`; use `moonpresschat-acceptance` for managing this isolated fixture. It does not test production marketplace naming.

No site credentials, local acceptance reports, release workflows or deployment configuration are included. GitHub Actions is disabled. This repository's version numbers are test markers, not canonical product releases.
