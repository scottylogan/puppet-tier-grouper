# grouper

#### Table of Contents

1. [Overview](#overview)
2. [Module Description - What the module does and why it is useful](#module-description)
3. [Setup - The basics of getting started with grouper](#setup)
4. [Usage - Configuration options and additional functionality](#usage)
5. [Limitations - OS compatibility, etc.](#limitations)

## Overview

Installs and configures Grouper for TIER.

## Module Description

This module installs Grouper using the Grouper Installer, then
configures tomcat and grouper.

## Setup

* Grouper is installed under `/opt/grouper`

## Usage

Use the `grouper::install` class to install Grouper (one-time):

    include grouper::install

Use the `grouper` class to configure Grouper (ongoing):

    include grouper

## Limitations

Only tested on CentOS 7.
