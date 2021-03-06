# Changelog

## 9th May 2018 22:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `502`.

## 18th April 2018 21:00 UTC

[Change Notification](channel-manager-api.md#change-notification) extened with a `type` property of [`Change Notification Type`](channel-manager-api.md#change-notification-type) type, that determines a type of change that happened in Mews.

## 28th March 2018 22:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `500`.

## 8th March 2018 22:00 UTC

[Process Group](mews-api.md#process-group) API call:

Following changes are done in a way that the previous fields still exist in both API and are still supported and the new fields are added next to it and used the same way as their previous versions:

* `cvv` field added to [`Payment card`](mews-api.md#payment-card) object.
* ~~code~~ was removed and replaced with `type` in [`Payment card`](mews-api.md#payment-card) object.

**The support is temporarily and will end approximately by end of April 2018. Make sure you migrate to use the new fields, as the previous fields will be removed.**

## 1th March 2018 22:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `500`.

## 7th February 2018 23:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `443`.

## 18th January 2018 00:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `441`.

## 10th January 2018 22:00 UTC

[Get Configuration](mews-api.md#get-configuration) API call:

* `applicability` field added to [`Cancellation Policy`](mews-api.md#cancellation-policy) object.

Following changes are done in a way that the previous fields still exist in both API and are still supported and the new fields are added next to it and used the same way as their previous versions:

* ~~accessToken~~ renamed to `clientToken` in all API calls in **both** API sides.
* ~~connectionCode~~ renamed to `connectionToken`in all API calls in **both** API sides.
* [Get Properties](mews-api.md#get-properties) API call
  * ~~code~~ renamed to `token` in [`Connection Info`](mews-api.md#connection-info) object.
* [Process Group](mews-api.md#process-group) API call
  * ~~distributor~~ renamed to `channel` in [`Reservation`](mews-api.md#reservation) object.

**The support is temporarily and will end approximately by end of March 2018. Make sure you migrate to use the new fields, as the previous fields will be removed.**

## 13th December 2017 00:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `425`.

## 30th November 2017 00:00 UTC

[Channel](channels.md#channels) list extended. The latest Channel added has code `423`.

## 15th October 2017 22:00 UTC

Initial version released.

