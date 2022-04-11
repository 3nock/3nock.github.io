---
title: Sub3 Suite
icon: fas fa-info-circle
order: 1
---

# Getting started with [Sub3 Suite](https://github.com/3nock/sub3suite)

## Launching 

Download Sub3 Suite for your required platform (Windows or Linux) from [releases](https://github.com/3nock/sub3suite/releases).

**on Windows**

After download: Extract the zip file to location of your choice. To run just open the `sub3suite.exe` application and done!

***NOTE:***

1. Install the MSVC-redistributable package `sub3suite/vcredist_x64.exe` or `sub3suite/vcredist_x86.exe` if the program fails to run on first try.

2. Install the OpenSSL libraries using OpenSSL package `sub3suite/Win32 OpenSSL v1.1.1n Light.msi` or `sub3suite/Win64 OpenSSL v1.1.1n Light.msi` in your system incase of SSL errors when using sub3suite.

**on Linux**

After download: Extract archive with command `tar -xvf sub3suite-<version>-linux.tar.gz`, then `cd sub3suite` and run sub3suite `./sub3suite`.

## Startup wizard

When Sub3 Suite launches, the startup wizard is displayed. This lets you choose what s3s project to open.

### Selecting a project

You can choose from the following options to create or open a project:

`Temporary project` - This option is useful for quick tasks where your work doesn't need to be saved. All data is held in memory, and is lost when s3s exits.

`New project on disk` - This creates a new project that will store its data in a s3s project file. This file will hold all of the data and configuration for the project. You can also specify a name for the project.

`Open existing project` - This reopens an existing project from a Sub3 project file. A list of recently opened projects is shown for quick selection. 

***Note:***

*You can rename a project later via project config.*

## Tools Suite

Use the links below for further help on Sub3 Suite Engines:

1. [OSINT](sub3suite/engines/osint.md) Engine.
2. [RAW](sub3suite/engines/raw.md) Engine.
3. [BRUTE](sub3suite/engines/brute.md) Engine.
4. [ACTIVE](sub3suite/engines/active.md) Engine.
5. [DNS](sub3suite/engines/dns.md) Engine.
6. [SSL](sub3suite/engines/ssl.md) Engine.
7. [URL](sub3suite/engines/url.md) Engine.

Use the links below for further help on Sub3 Suite Enumerators:

1. [IP](sub3suite/enums/ip.md) Enumerator.
2. [ASN](sub3suite/enums/asn.md) Enumerator.
3. [CIDR](sub3suite/enums/cidr.md) Enumerator.
4. [NS](sub3suite/enums/ns.md) Enumerator.
5. [MX](sub3suite/enums/mx.md) Enumerator.
6. [SSL](sub3suite/enums/ssl.md) Enumerator.
7. [EMAIL](sub3suite/enums/email.md) Enumerator.