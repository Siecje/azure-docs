---
title: include file
description: include file
services: media-services
author: Juliako
ms.service: media-services
ms.topic: include
ms.date: 01/28/2019
ms.author: juliako
ms.custom: include file
---

## CLI Shell

It is recommended to use [Azure Cloud Shell](https://docs.microsoft.com/azure/cloud-shell/overview?view=azure-cli-latest) to execute CLI commands. **Cloud Shell** is a free, interactive shell that you can use to run the steps in this article. Common Azure tools are preinstalled and configured in Cloud Shell for you to use with your account. It provides the flexibility of choosing the shell experience that best suits the way you work. Linux users can opt for a Bash experience, while Windows users can opt for PowerShell.

If you choose to install and use the CLI locally, this article requires that you are running the Azure CLI version 2.0 or later. Run `az --version` to find the version. If you need to install or upgrade, see [Install the Azure CLI](https://docs.microsoft.com/cli/azure/install-azure-cli?view=azure-cli-latest). 

### Login

To start using the CLI shell (in the cloud or locally), run `az login` to create a connection with Azure.

If the CLI can open your default browser, it will do so and load a sign-in page. Otherwise, you need to open a browser page and follow the instructions on the command line to enter an authorization code after navigating to https://aka.ms/devicelogin in your browser.

### Specify location of files

Many Media Services CLI commands allow you to pass a parameter with a file name. If you are using **Cloud Shell**, you can upload your file to your clouddrive (using Bash or PowerShell). 

![Upload files]

Whether you are using a local CLI or **Cloud Shell**, you need to specify the file path according to the OS or Cloud Shell (Bash or PowerShell) that you are using. Below are some examples:

Relative path to the file (all OS)

* `@"mytestfile.json"`
* `@"../mytestfile.json"`

Absolute file path on Linux/Mac and Windows OS

* `@ "/usr/home/mytestfile.json"`
*	`@"c:\tmp\user\mytestfile.json"`


[Upload files]: ./media/media-services-cli/upload-download-files.png
