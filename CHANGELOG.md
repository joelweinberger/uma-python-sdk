# Changelog

## v0.3.0

- Switch `display_decimals` to `decimals` to better match a LUD-21 proposal after discussions with the author.

## v0.2.2

- IMPORTANT: Fix a bug with signature validation to actually ensure the signature matches the pubkey.

## v0.2.1

- Handle null expiration correctly when parsing pubkey responses.

## v0.2.0

- Add the display_decimals field to the currency object in the lnurlp response.

## v0.1.6

- Missed one other mismatched serialized field name.

## v0.1.5

- Fix the serialized names of several fields.

## v0.1.4

- Fix a bug in loading key.

## v0.1.3

- Fix a typo in the pubkey JSON seriailzation.

## v0.1.2

- Support both der and compressed key.

## v0.1.1

- Add optional travel_rule_format to the payreq request.

## v0.1.0

- First version of UMA.