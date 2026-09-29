# Shiryu.Shaders.PoiyomiPro

`Shiryu.Shaders.PoiyomiPro` is the Shiryu Studios VPM integration package for Poiyomi Pro.

## What this package does

- Adds the official Poiyomi Pro VPM package as a dependency.
- Keeps Poiyomi Pro installation and authentication on Poiyomi's official distribution path.
- Lets ShiryuVPM users resolve Poiyomi Pro alongside other Shiryu Studios packages.

## What this package does not do

This repository does **not** redistribute the paid `_PoiyomiShaders` payload or bypass Poiyomi's Patreon authentication. The actual shader package remains provided by Poiyomi through `com.poiyomi.pro`.

## Install

Add the Shiryu Studios VPM repository:

`https://packages.shiryu.org/official?download`

Then install **Shiryu.Shaders.PoiyomiPro**. VPM will resolve the official `com.poiyomi.pro` dependency. Poiyomi's installer will handle any required Patreon authentication and shader download.

## Package IDs

- Shiryu integration: `org.shiryu.shaders.poiyomipro`
- Official Poiyomi Pro dependency: `com.poiyomi.pro`

## Ownership

The Shiryu integration package, metadata, documentation, and release automation in this repository are maintained by Shiryu Studios LLC.

Poiyomi Pro, its shaders, trademarks, and associated assets belong to their respective owners and are not included in this repository.
