# Well Known

**Note: This is a work in progress repository**

This respository is a community driven repository of well known addresses, OUIs, etc. on the Helium network.

## OUIs

OUIs (Organizationally Unique Identifiers) are the way that LoRaWAN Network Servers register with the Helium Network. It may be helpful for the community to know which individual or entity is running each LNS for analytics purposes.

To view the current list of known OUIs, check out [ouis.json](/lists/ouis.json).

To submit your OUI to the list, submit a PR with your OUI added as the last object in the array in `ouis.json` with the following object format:

```json
{
    "id": 1,
    "escrow_account": "6QQNxU671ztxwEcNZn1qvA5KXv6Lb3objKDU3pBqc96w",
    "name": "Helium Foundation Console"
}
```
