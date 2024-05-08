# Well Known

This respository is a community driven repository of well known addresses, OUIs, etc. on the Helium network.

## OUIs

OUIs (Organizationally Unique Identifiers) are the way that LoRaWAN Network Servers register with the Helium Network. It may be helpful for the community to know which individual or entity is running each LNS for analytics purposes.

To view the current list of known OUIs, check out [lists/ouis.json](/lists/ouis.json).

To submit your OUI to the list, submit a PR with your OUI added as the last object in the array in `ouis.json` with the following object format:

```json
{
    "id": 1,
    "router_key": "112qB3YaH5bZkCnKA5uRH7tBtGNv2Y5B4smv1jsmvGUzgKT71QpE",
    "escrow_account": "6QQNxU671ztxwEcNZn1qvA5KXv6Lb3objKDU3pBqc96w",
    "name": "Helium Foundation Console"
}
```

## Providers
To view the current list of known public connectivity providers using Helium, check out [lists/lns-providers/providers.json](lists/lns-providers/providers.json).  
The list in this repository backs public lists such as [Find an LNS Provider](https://docs.helium.com/iot/find-a-lns-provider) in Helium Docs.

Please consider submitting your Helium business if it meets these critera:
- Have onboarded 200+ sensors and product is ready commercially.
- Have a professional website & landing page outlining Helium service offering.
- Offering is available to the public regardless of sensor type or brand. Please add any scale requirements in the description section if applicable.
