---
id: overview
title: CISA Entra Controls
sidebar_label: Entra
description: Implementation of CISA Entra Controls
---

```mdx-code-block

# CISA Entra Controls

## Overview

The tests in this section closely align to the Cybersecurity and Infrastructure Security Agency (CISA) Secure Cloud Business Applications (SCuBA) Project implementation.

## Tests

* Test-MtCisaActivationNotification - [MS.AAD.7.9](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad79v1)
* Test-MtCisaActivationNotification - [MS.AAD.7.8](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad78v1)
* Test-MtCisaAppAdminConsent - [MS.AAD.5.3](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad53v1)
* Test-MtCisaAppGroupOwnerConsent - [MS.AAD.5.4](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad54v1)
* Test-MtCisaAppRegistration - [MS.AAD.5.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad51v1)
* Test-MtCisaAppUserConsent - [MS.AAD.5.2](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad52v1)
* Test-MtCisaAssignmentNotification - [MS.AAD.7.7](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad77v1)
* Test-MtCisaAuthenticatorContext - [MS.AAD.3.3](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad33v1)
* Test-MtCisaBlockHighRiskSignIn - [MS.AAD.2.3](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad23v1)
* Test-MtCisaBlockHighRiskUser - [MS.AAD.2.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad21v1)
* Test-MtCisaBlockLegacyAuth - [MS.AAD.1.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#1-legacy-authentication)
* Test-MtCisaCloudGlobalAdmin - [MS.AAD.7.3](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad73v1)
* Test-MtCisaGlobalAdminCount - [MS.AAD.7.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad71v1)
* Test-MtCisaGlobalAdminRatio - [MS.AAD.7.2](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad72v1)
* Test-MtCisaGuestInvitation - [MS.AAD.8.2](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad82v1)
* Test-MtCisaGuestUserAccess - [MS.AAD.8.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad81v1)
* Test-MtCisaManagedDevice - [MS.AAD.3.7](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad37v1)
* Test-MtCisaManagedDeviceRegistration - [MS.AAD.3.8](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad38v1)
* Test-MtCisaMethodsMigration - [MS.AAD.3.4](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad34v1)
* Test-MtCisaMfa - [MS.AAD.3.2](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad32v1)
* Test-MtCisaNotifyHighRisk - [MS.AAD.2.2](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad22v1)
* Test-MtCisaPasswordExpiration - [MS.AAD.6.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad61v1)
* Test-MtCisaPermanentRoleAssignment - [MS.AAD.7.4](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad74v1)
* Test-MtCisaPhishResistant - [MS.AAD.3.1](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad31v1)
* Test-MtCisaPrivilegedPhishResistant - [MS.AAD.3.6](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad36v1)
* Test-MtCisaRequireActivationApproval - [MS.AAD.7.6](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad76v1)
* Test-MtCisaUnmanagedRoleAssignment - [MS.AAD.7.5](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad75v1)
* Test-MtCisaWeakFactor - [MS.AAD.3.5](https://github.com/cisagov/ScubaGear/blob/main/PowerShell/ScubaGear/baselines/aad.md#msaad35v1)


```
