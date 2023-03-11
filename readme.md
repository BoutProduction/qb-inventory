
## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-logs](https://github.com/qbcore-framework/qb-logs) - For logging transfer and other history
- [qb-traphouse](https://github.com/qbcore-framework/qb-traphouse) - Trap house system for qbcore
- [qb-radio](https://github.com/qbcore-framework/qb-radio) - Radio system for communication
- [qb-drugs](https://github.com/qbcore-framework/qb-drugs) -  Drugs and Weed Planting System
- [qb-shops](https://github.com/qbcore-framework/qb-shops) - Needed in order to add shops

## Screenshots
![General](https://user-images.githubusercontent.com/127620206/224503455-d8e085d3-e82b-407e-adbb-1260ffd7966c.png)

## Features
- Item crafting
- Weapon attachment crafting
- Stashes (Personal and/or Shared)
- Vehicle Trunk & Glovebox
- Weapon serial number
- Shops
- Item Drops

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Import `qb-inventory.sql` in your database
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure qb-logs
ensure qb-inventory
ensure qb-traphouse
ensure qb-radio
ensure qb-drugs
ensure qb-shops
```
