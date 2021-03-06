---
title: TPM 2.0 - Required Security Patches Tests
description: TPM 2.0 - Required Security Patches Tests
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 7012c7ec-0c24-4393-a709-8535892108c8
author: EliotSeattle
ms.author: eliotgra
ms.date: 10/15/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---

# <span id="p_hlk_test.b2bdd98b-3dca-4d3b-8d3d-1bb9c614eb65"></span>TPM 2.0 - Required Security Patches Tests


This manual test validates the presence of all mandatory security critical patches that are released for the 0.88 version implementation of Trusted Platform Module (TPM).

## Test details
|||
|---|---|
| **Specifications**  | <ul><li>Device.TrustedPlatformModule.TPM20.Features</li></ul> |  
| **Platforms**   | <ul><li>Windows 10, client editions (x86)</li><li>Windows 10, client editions (x64)</li><li>Windows Server 2016 (x64)</li></ul> |
| **Supported Releases** | <ul><li>Windows 10</li><li>Windows 10, version 1511</li><li>Windows 10, version 1607</li><li>Windows 10, version 1703</li><li>Windows 10, version 1709</li></ul> |
|**Expected run time (in minutes)**| 40 |
|**Category**| Compatibility |
|**Timeout (in minutes)**| 80 |
|**Requires reboot**| false |
|**Requires special configuration**| false |
|**Type**| manual |

 

## <span id="Additional_documentation"></span><span id="additional_documentation"></span><span id="ADDITIONAL_DOCUMENTATION"></span>Additional documentation


Tests in this feature area might have additional documentation, including prerequisites, setup, and troubleshooting information, that can be found in the following topic(s):

-   [System.Fundamentals additional documentation](system-fundamentals-additional-documentation.md)

## <span id="Running_the_test"></span><span id="running_the_test"></span><span id="RUNNING_THE_TEST"></span>Running the test


Before you run the test, review the prerequisites in [TPM System Fundamentals Testing Prerequisites](tpm-system-fundamentals-testing-prerequisites.md).

This test has no additional test parameters

## <span id="Troubleshooting"></span><span id="troubleshooting"></span><span id="TROUBLESHOOTING"></span>Troubleshooting


For generic troubleshooting of HLK test failures, see [Troubleshooting Windows HLK Test Failures](..\user\troubleshooting-windows-hlk-test-failures.md).

For troubleshooting information, see [Troubleshooting Windows HLK Test Failures](..\user\troubleshooting-windows-hlk-test-failures.md).

This test returns Pass or Fail. To review test details, review the test log from Windows Hardware Lab Kit (Windows HLK) Studio. To provide more information for troubleshooting failures in this test, you can enable tracing of the TPM. Refer to the steps provided under the Troubleshooting section in [TCG TPM Integration Test (Manual)](https://msdn.microsoft.com/en-us/library/Hh998628.aspx). Investigations also need log files with name like 'tpm\*.txt' and console.txt from the 'Documents' folder

 

 






