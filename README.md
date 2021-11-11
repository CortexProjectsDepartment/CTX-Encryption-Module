<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-Encryption-Module
The module uses flows and subtasks to allow users to perform the following functionality:
 - Encrypt file(s) with AES256 Encryption
 - Decrypt file(s) with AES256 Encryption
 - Encrypt file(s) with PGP Encryption
 - Decrypt file(s) with PGP Encryption

* The flow uses LivePortal to allow the user to interactively Encrypt/Decrypt file(s) using a choice between AES256 or PGP Encryption methods.
* The subtasks allow the user to incorporate the encryption/decyrption functionality into their own flows.

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [Files](#files)
1) [Support and Warranty](#support-and-warranty)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-Encryption-Module was developed in Cortex v7.1.0. Some functionality may not be available in other verions of Cortex.

### OCIs
N/A

### Files
The CTX-Encryption-Module module requires the following files:
* [CTX-Encryption-Module Studio Package](https://github.com/CortexProjectsDepartment/CTX-Encryption-Module/releases/download/v1.0/Encryption-Module.studiopkg)

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](https://github.com/CortexProjectsDepartment/CTX-Encryption-Module/blob/main/CTX-Encryption-Moudle%20-%20Deployment%20Plan.pdf).

## How to use
A detailed User Guide has been provided with instructions on how to use the flows/subtasks, available [here](https://github.com/CortexProjectsDepartment/CTX-Encryption-Module/blob/main/CTX-Encryption-Module%20-%20User%20Guide.pdf). Configuring of the subtask's inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-Encryption-Module module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 09/09/2021 | Encryption-Decryption | Created


## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2019 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
