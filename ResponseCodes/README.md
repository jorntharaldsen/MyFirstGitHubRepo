# Response Codes

| RC |Description|
|---|---|
| 00 | Approved, *online* |
| Z3 | Declined, *could not* go online |
| Z1 | Declined, *no need* to go online |
| Y3 | Approved, *could not* go online |
| Y1 | Approved, *no need* to go online |
|---|---|
| ?? | Declined/Approved, *online*, See SDI protocol specification |

## Note

* Z3 and Y3 means we are OFFLINE.

* Y1 may happen frequently with EMV cards.

* Y3 means 'Approved with signature/id' in some regions!

* Z1 should not happen (frequently), if you expect it is valid cards being used. (Configuration error?).

* You should never see Y1 or Y3 if the terminal is configured as online-only!
