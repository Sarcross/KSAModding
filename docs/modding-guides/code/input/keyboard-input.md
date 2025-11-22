# Getting keyboard input from KSA

## Overview
This section will cover how to get keyboard input when modding KSA.

## Prerequisites
This guide uses harmony to intercept the `Vehicle.OnKey` function calls so we will need that setup first.
This guide continues from [Getting started with harmony](../harmony.md)

for this guide you will need:
* A visual studio solution set up for StarMap modding and with HarmonyLib as a NuGet package
* The Patcher class from [the previous guid](../harmony.md)