# dsh-calendar — Privacy Policy

_Last updated: 2026-10-13_

`dsh-calendar` is a personal, single-user tool. It is an OAuth client that lets its
owner (and only its owner) read and write their own Google Calendar from a local
command-line agent running on their own computer.

## What it accesses

Only the Google Calendar scope the owner grants during consent
(`https://www.googleapis.com/auth/calendar`). That means events on the owner's own
calendar: titles, times, locations, descriptions and attendees.

## Where the data goes

Nowhere except back to Google. Calendar data is requested from Google's API, shown
to the owner in their own terminal or chat, and is not sent to any other server,
analytics service, or third party. There is no backend, no database, and no account
system.

## What is stored, and where

Exactly one credential is stored: the OAuth refresh token, on the owner's own
machine, in a local configuration file readable only by that user. No calendar
content is stored on disk beyond what the owner explicitly exports.

## Sharing

No data is sold, shared, transferred, or disclosed to anyone. No advertising. No
profiling.

## Revoking access

The owner can revoke this client at any time at
<https://myaccount.google.com/permissions>, which immediately invalidates the stored
token.

## Contact

a1360201628@gmail.com
