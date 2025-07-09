# DG-Dlib-Transform-

This plugin aims to integrate a private lib called Dlib, developed to allow the player to transform into entities, perform registered animations, and be compatible with the modded entity, geckolib, and mcreator's own animation system.

Why use my plugin?
Dlib was developed especially for modders, giving them access to all functions only through my plugin. The goal is to be better than public transformation mods like WoodWalkers and Identity.
Dlib is a private plugin developed by my team and will be used in several of my projects in the future.

Spoiler -- Dragon Life - Solo Craft

Usage rights:

This is a demo version, with initial support for Dlib version 1.0.

It also adds some Blocklys:

![Dlib V1.0](https://i.ibb.co/TqqcdmPk/dlib-v1.png)

---

For now, only 1.20.1 is supported.

The subscription version will include all Dlib support.

Dlib is currently in version 2.0, adding support for ModelPart manipulation, arm manipulation, and more.

Note: The lib is ready, but the plugin implementation is not finalized.

Premium Support will be available soon.

How does the plugin work?

Like DG Mods Transform, DG Dlib Transform has an API application. When enabled, it creates a folder called jarjar, which initially contains the "dlib_integrated" file, which is responsible for integrating the lib.
Set to true or false;

If true, implementation occurs directly in the main mod, without generating dependencies, adding to the basic implementation of a composite mod.

If false, implementation will be via dependency, requiring the lib's .jar file.

It also generates a file required for implementation called "metadata." Only edit it if you know what you're doing.

When exporting, the same "metadata" file will be copied to its proper location.

## Current Changelog

### v1.0
- Start of plugin.

---

If you want to support my work 👉 [Offer a gem!!](https://ko-fi.com/L4L61GU6V3)