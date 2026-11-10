# Alteryx Whitelist

Alteryx One network whitelisting requirements.

## Table of Contents <!-- omit in toc -->

1. [Resources](#resources)
2. [Domains](#domains)
3. [IP Addresses](#ip-addresses)
4. [Offline Activation](#offline-activation)

## Resources

1. [Get Started with Alteryx One Platform](https://help.alteryx.com/aac/en/platform/getting-started-with-alteryx-one.html)
2. [Seamless Setup: Activating and Managing Alteryx One](https://knowledge.alteryx.com/index/s/article/Alteryx-One-Onboarding)
3. [Verification code not received](https://knowledge.alteryx.com/index/s/article/Verification-code-not-received)

## Domains

| Category | Domain | Details |
| --- | --- | --- |
| Alteryx One Access | `cdn.alteryxcloud.com` | Alteryx One Admin Portal page content |
| Alteryx One Access | `us1.alteryxcloud.com` | US (us1) Control Plane |
| Alteryx One Access | `eu1.alteryxcloud.com` | EMEA (eu1) Control Plane |
| Alteryx One Access | `au1.alteryxcloud.com` | APAC (au1) Control Plane |
| Licensing & Entitlement | `whitelist.alteryx.com` | Main gateway |
| Licensing & Entitlement | `licenses.alteryx.com` | Alias for Legacy Flexera  License Portal <https://us1.alteryxcloud.com/license-portal> |
| Licensing & Entitlement | `fno.devops.alteryx.com` | License activation check |
| Authentication | `pingauth.alteryxcloud.com` | US (us1) authentication portal (required to enable online activation) |
| Authentication | `pingauth-us1-1.alteryxcloud.com` | US (us1) Workspace authentication SSO callback |
| Authentication | `pingauth-us1-2.alteryxcloud.com` | US (us1) Account authentication SSO callback |
| Authentication | `pingauth-eu1.alteryxcloud.com` | EMEA (eu1) authentication portal |
| Authentication | `pingauth-eu1-1.alteryxcloud.com` | EMEA (eu1) Workspace authentication SSO callback |
| Authentication | `pingauth-au1.alteryxcloud.com` | APAC (au1) authentication portal |
| Authentication | `auth.customer-login.alteryx.com` | Login redirection (My Alteryx) |
| Support & Knowledge | `my.alteryx.com` | Support Portal |
| Support & Knowledge | `api.my.alteryx.com` | Support Portal API |
| Support & Knowledge | `knowledge.alteryx.com` | Knowledge Base |
| Support & Knowledge | `myalteryx.com` | Alias for <https://my.alteryx.com> |
| Documentation & Community | `help.alteryx.com` | Online Documentation |
| Documentation & Community | `community.alteryx.com` | Community Forum |
| Documentation & Community | `gallery.alteryx.com` | Alias for <https://community.alteryx.com/t5/Community-Gallery/ct-p/Community-gallery> |
| Documentation & Community | `license.alteryx.com` | Alias for <https://community.alteryx.com/t5/Community-Gallery/ct-p/Community-gallery> |
| Documentation & Community | `academy.alteryx.com` | Academy Learning Portal |
| Downloads | `downloads.alteryx.com` | Alias for Legacy Flexera Download Portal <https://us1.alteryxcloud.com/license-portal> |
| Corporate / Marketing | `alteryx.com` | Main Corporate Website |
| Corporate / Marketing | `www.alteryx.com` | Main Corporate Website |
| Telemetry & Monitoring | `sentry.my.alteryx.com` | Telemetry Gateway |
| Email | `mail.alteryxcloud.com` | Alteryx One Email SMTP |
| Email | `mail.my.alteryx.com` | Alteryx Support Portal SMTP |
| Email | `myalteryx.alteryx.com` | Alteryx Support Portal SMTP |

## IP Addresses

| Region | Location | Control Plane IP Addresses | Data Plane IP Addresses |
| --- | --- | --- | --- |
| US (us1) | Oregon, US | `34.82.130.80/29` `54.240.127.79` `54.240.127.78` `198.244.48.34` | `44.225.183.12/32` `52.89.130.54/32` `35.163.16.225/32` |
| EMEA (eu1) | Frankfurt, Germany | `34.89.162.16/29` `54.240.127.79` `54.240.127.78` `198.244.48.34` | `3.73.229.70/32` `3.74.64.229/32` `3.78.97.169/32` |
| APAC (au1) | Sydney, Australia | `34.40.128.80/29` `54.240.127.79` `54.240.127.78` `198.244.48.34` | `13.210.106.106/32` `3.105.170.156/32` `52.63.126.137/32` |

## Offline Activation

1. [Activate License Offline with Alteryx One Platform](https://help.alteryx.com/20251/en/license-and-activate/license-and-activate-with-alteryx-one/activate-license-offline-with-alteryx-one.html)
2. [Activate Alteryx offline using `.bin` files](https://knowledge.alteryx.com/index/s/article/Fulfillment-activate-Alteryx-offline-using-bin-files)
3. [Offline license activation](https://knowledge.alteryx.com/index/s/article/Offline-license-activation)

**Note**: The offline activation file is in binary format (`.bin`). This can cause issues with firewalls or IT policies, which may corrupt the file while moving it to the machine where it must be activated.

**Workaround**: Modify the file extension after download (for example, `.YXZP`) and revert it back before activating in Designer.
