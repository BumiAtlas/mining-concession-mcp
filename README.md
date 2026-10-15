# Indonesia Mining Concession MCP (ESDM IUP)

Connect your AI assistant to [BumiAtlas](https://bumiatlas.com) for research on Indonesian mining licences through the Model Context Protocol.

This listing is a focused entry point for:

- Mining licences from ESDM: IUP, IUPK, Kontrak Karya (KK), PKP2B, IPR, and WIUP/WIUPK licence areas
- Holder and corporate group
- Commodity (nickel, coal, gold, bauxite, tin...), in ESDM's Indonesian name and in English
- Stage (exploration, production, reserved area, post-mining), start and end dates, regency and province
- Area and boundary, and natural forest left inside the licence area

The MCP connection is provided by BumiAtlas. This repository does not run a separate server. For parcels, HGU, mining and zoning in one connection, use [BumiAtlas MCP](https://github.com/BumiAtlas/bumiatlas-mcp).

## Connect

```
https://bumiatlas.com/mcp/mining
```

Add it as a custom connector in any MCP client and sign in with Google. More: [bumiatlas.com/konsesi/tambang](https://bumiatlas.com/konsesi/tambang).

## Tools

| Tool | Description |
|---|---|
| `Mining_search` | Search licences by holder, group, commodity, licence type, stage, regency/province, or active/expired |
| `Mining_get` | Full licence record: holder, group, licence type, stage, commodity, start and end dates, area, remaining natural forest; boundary as GeoJSON |

## Example prompts

- *"List the nickel mining licences in Sulawesi Tenggara"*
- *"Which coal IUP in Kalimantan Timur have expired?"*
- *"What licences does the Harita group hold, and for which commodities?"*
- *"How much natural forest is left inside the largest coal concessions in Kalimantan Timur?"*
- *"Show the gold mining licences in production stage in Maluku Utara"*

## Data source

ESDM mining licence areas (via Nusantara Atlas). Boundaries are accurate to about 11 m.
