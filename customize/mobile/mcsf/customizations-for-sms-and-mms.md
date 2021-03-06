---
title: Customizations for SMS and MMS
description: Contains settings that you can configure for SMS and MMS.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 765e9d5b-87d9-49f2-8b16-3d54cb364643
author: themar-msft
ms.author: themar
ms.date: 05/02/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---
# Customizations for SMS and MMS

Contains settings that you can configure for SMS and MMS.

## In this section

| Topic                                 | Description                                                                                   |
|:--------------------------------------|:----------------------------------------------------------------------------------------------|
| [Add encoding extension tables for SMS](add-encoding-extension-tables-for-sms.md) | Partners can extend the set of supported SMS encodings.   |
| [Automatic send retry and resize settings for MMS messages](automatic-send-retry-and-resize-settings-for-mms-messages.md) | For MMS messages that have photo attachments and that fail to send, partners can choose to automatically resize the photo and attempt to resend the message.  |
| [Automatically retry downloading MMS messages](automatically-retry-downloading-mms-messages.md)   | Partners can configure the messaging app to automatically retry downloading an MMS message if the initial download attempt fails. |
| [Content location in the multimedia message service center (MMSC)](content-location-in-the-multimedia-message-service-center--mmsc-.md)   | For networks that require it, partners can specify the default GET path within the MMSC to use when the GET URL is missing from the WAP push MMS notification.    |
| [Delay for resend attempts](delay-for-resend-attempts.md) | If an SMS message fails to send correctly, partners can specify the number of additional attempts and the minimum delay between them in seconds.  |
| [Disable editing of the SMS center number](disable-editing-of-the-sms-center-number.md)   | To meet market or mobile operator requirements, OEMs can configure a setting to prevent users from editing the **SMS center number** in the messaging settings CPL.   |
| [Disable the EMS long messages feature](disable-the-ems-long-messages-feature.md) | Partners can disable the enhanced messaging service (EMS), which concatenates text messages so that the user can enter more than 160 characters in a single message.  |
| [Expiration time for SMS messages](expiration-time-for-sms-messages.md)   | Partners can set the expiration time before the device deletes the received parts of a long SMS message.  |
| [Extract phone numbers in strings](extract-phone-numbers-in-strings.md)   | Partners can extend the entity extraction feature that recognizes phone numbers in text. This customization allows strings of numbers that are concatenated to a string to be recognized. |
| [Full error messages for SMS and MMS](full-error-messages-for-sms-and-mms.md) | Partners can choose to display additional content in the conversation view when an SMS or MMS message fails to send.  |
| [IMS retry](ims-retry.md) | For networks that support it, when an outgoing SMS message fails to send due to a transient error, partners can specify the threshold for the number of attempts to resend the SMS over IMS before switching over to 3GPP or 3GPP2.   |
| [IMSI authentication](imsi-authentication.md) | For networks that require it, MMS messages can include the IMSI in the GET and POST header that the message center uses to authenticate the mobile subscriber.   |
| [International assisted dialing for SMS](international-assisted-dialing-for-sms.md)   | If partners have turned off [Assistance for dialing international phone numbers](assistance-for-dialing-international-phone-numbers.md), partners may still override the MCC and MNC used for plus code replacement when sending SMS. |
| [Maximum length for SMS messages](maximum-length-for-sms-messages.md) | Partners can specify a maximum length for SMS messages.  |
| [Maximum number of attachments for MMS messages](maximum-number-of-attachments-for-mms-messages.md)   | Partners can specify the maximum number of attachments for MMS messages, from 1 to 20.    |
| [Maximum number of recipients for SMS and MMS](maximum-number-of-recipients-for-sms-and-mms.md)   | Partners can set the maximum number of recipients to which a single SMS or MMS message can be sent.   |
| [MMS APN settings](mms-apn-settings.md)   | Partners can choose to display an **Add MMS APN** or **Edit MMS APN** button that enables the user to configure the APN used for MMS.   |
| [MMS automatic download](mms-automatic-download.md)   | Partners can choose to display an **Automatically download MMS** toggle to allows users to turn off automatic downloads of MMS messages. If the toggle is displayed, partners can also change the default value to stop automatic MMS downloads. |
| [MMS data options](mms-data-options.md)  | Partners can configure the MMS data options to show the **Allow MMS if cellular data is off** toggle in the **Messaging** settings screen, allow MMS messaging even if data is turned off, and allow MMS messaging even if data is turned off and the user is roaming.   | [MMS delivery confirmation](mms-delivery-confirmation.md)  | Partners can specify whether users receive notification that MMS messages could not be delivered, and determine whether users can control this by using the **MMS delivery confirmation** toggle in the **Messaging** settings screen.  |
| [MMS for group messages](mms-for-group-messages.md)   | For the setting that determines if group messages sent to multiple people must be sent as MMS, partners can customize the setting by hiding or showing the **Group Text** toggle in the **Messaging** settings screen, changing the default value, and configuring the option to alert the user of possible additional charges for sending a group text as MMS. |
| [MMS receipt acknowledgement](mms-receipt-acknowledgement.md) | Partners can specify whether the device automatically sends a receipt acknowledgment for MMS messages when messages arrive, and allow users to control the receipt acknowledgments by using the **Send MMS acknowledgement** toggle in the <strong>Messaging</strong> setting screen.    |
| [Permanent SMS message failures](permanent-sms-message-failures.md)   | Partners can mark SMS message failures as permanent failures so that the user will not be given the option to attempt to resend the SMS.  |
| [Ports that accept cellular broadcast messages](ports-that-accept-cellular-broadcast-messages.md) | Partners can specify one or more ports from which the device will accept cellular broadcast messages. |
| [Proxy authorization for MMS](proxy-authorization-for-mms.md) | Partners can specify the use of NAI information as a dedicated header for MMS authentication for mobile networks that require this functionality. The string value must be the MMS header used for authentication.    |
| [Select multiple recipients for SMS and MMS messages](select-multiple-recipients-for-sms-and-mms-messages.md) | Partners can show the **select all contacts**/**unselect all** menu option to allow users to easily select multiple recipients for an SMS or MMS message. |
| [Send SMS messages to SMTP addresses](sending-sms-messages-to-smtp-addresses.md)   | Partners can configure SMS messages to be sent to email addresses as well as phone numbers.   |
| [Server for MMS acknowledgement messages](server-for-mms-acknowledgement-messages.md) | By default, the MMS transport sends an acknowledgement to the provisioned MMS application server (MMSC). However, on some networks, the correct server to use is sent as a URL in the MMS message. In that case, a registry key must be set, or else the acknowledgement will not be received and the server will continue to send duplicate messages.    |
| [SMS delivery confirmation](sms-delivery-confirmation.md) | Partners can specify whether users receive notification that SMS messages could not be delivered, and determine whether users can control these notifications by using the **SMS delivery confirmation** toggle in the **Messaging** settings screen.   |
| [SMS encoding](sms-encoding.md)   | Partners can change the default GSM 7-bit code page decoding and encoding, and can also extend the set of supported SMS encodings by setting an **always on** GSM 7-bit shift table, adding encoders, and adding decoders.    |
| [SMS intercept deny list](sms-intercept-deny-list.md) | OEMs can specify one or more filters in order to intercept incoming SMS messages intended for mobile operator partner applications that are not installed on the device.  |
| [SMS intercept ports](sms-intercept-ports.md) | OEMs can configure ports on which a Wireless Application Protocol (WAP)-formatted message can be intercepted by the mobile operator app.  |
| [Support HTTP cache-control no-transform for MMS](support-http-cache-control-no-transform-for-mms.md) | For networks that require it, OEMs can add support for the HTTP header Cache-Control No-Transform directive for MMS messages. |
| [Supported protocols for service indication messages](supported-protocols-for-service-indication-messages.md) | Partners can add additional supported protocols for service indication messages.  |
| [Switch from SMS to MMS for long messages](switch-from-sms-to-mms-for-long-messages.md)   | For networks that do support MMS and do not support segmentation of SMS messages, partners can specify an automatic switch from SMS to MMS for long messages. |
| [Truncated content handling for WAP push notification](truncated-content-handling-for-wap-push-notification.md)   | For networks that require non-standard handling of single-segment incoming MMS WAP Push notifications, partners can specify that MMS messages may have some of their content truncated and that they may require special handling to reconstruct truncated field values.  |
| [Use insert-address-token or local raw address](use-insert-address-token-or-local-raw-address.md) | To meet certain mobile operator requirements, OEMs can customize the OS image to use either the insert-address-token or the local raw address for the **From** field in MMS messages.    |
| [Use UTF-8 for MMS messages with unspecified character encoding](use-utf-8-for-mms-messages-with-unspecified-character-encoding.md)   | Some incoming MMS messages may not specify a character encoding. To properly decode MMS messages that do not specify a character encoding, OEMs can set UTF-8 to decode the message.  |
| [User agent profile for MMS messages](user-agent-profile-for-mms-messages.md) | Partners can specify a user agent profile to use on the device for MMS messages.  |
| [User agent string for MMS messages](user-agent-string-for-mms-messages.md)   | Partners can replace the entire user agent string for MMS.    |
| [User alert for service indication messages](user-alert-for-service-indication-messages.md)   | Partners can hide the user prompts for signal-medium messages.    |
| [Video attachments in MMS](video-attachments-in-mms.md)   | Partners can specify the transcoding to use for video files sent as attachments in MMS messages.  |
| [Voicemail SMS intercept](voicemail-sms-intercept.md)   | Partners can define a filter that intercepts an incoming SMS message and triggers visual voicemail synchronization. The filtered message does not appear in the user’s conversation list.   |

## Related topics

[Prepare for Windows mobile development](https://docs.microsoft.com/en-us/windows-hardware/manufacture/mobile/preparing-for-windows-mobile-development)

[Customization answer file overview](https://docs.microsoft.com/en-us/windows-hardware/customize/mobile/mcsf/customization-answer-file)
