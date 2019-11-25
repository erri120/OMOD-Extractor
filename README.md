# OMOD-Framework

**THIS PROJECT IS DEPRECATED! USE [this](https://github.com/erri120/OMODFramework) instead**

[![Documentation Status](https://readthedocs.org/projects/omod-framework/badge/?version=latest)](https://omod-framework.readthedocs.io/en/latest/?badge=latest)
[![Build Status](https://dev.azure.com/erri120/OMOD-Framework/_apis/build/status/erri120.OMOD-Framework?branchName=master)](https://dev.azure.com/erri120/OMOD-Framework/_build/latest?definitionId=1&branchName=master)
![Nuget](https://img.shields.io/nuget/v/erri120.OMODFramework)

This framework contains code of the original Oblivion Mod Manager aka [OBMM](https://www.nexusmods.com/oblivion/mods/2097).

OBMM is old. First uploaded on 31 March 2006 to the Nexus it has been over 9 years since the last update from February 2010. The bright side is that the author Timeslip made the source code for OBMM publicly available under the GPLv3 license.

This framework is meant to be a helper for all tools that want to do something with `.omod` files. Initialy just an extractor, this framework can now execute the installation script inside an OMOD with your own created UI.

## Features

1. Extraction of OMOD files
2. Parsing of information inside OMODs
3. Running the installation script (obmmScript, cSharp and VB)

## Missing features

- Python script execution
- Wrapper for different languages

## Usage

An example project is available in the [repo](https://github.com/erri120/OMOD-Framework/blob/master/OMOD-Framework-Example/Program.cs) and explains in-depth, how to use this framework for installing `.omod` files.

The documentation is available on [readthedocs.io](https://omod-framework.readthedocs.io/)
