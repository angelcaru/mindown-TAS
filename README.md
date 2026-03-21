# Celeste Minimum Down Presses TAS Inputs
Celeste TAS Inputs pressing Down and Crouch Dash as few times as possible. Spreadsheet: https://docs.google.com/spreadsheets/d/1AIq4PyfsyGginqy3aZAMkBLc3YNZVxj3PZLedTg3fao/edit?gid=379477008#gid=379477008

## Rulesets Explanation (this is also in the spreadsheet)
There are 32 different rulesets, each a combination of the following 5 letters:
- `D`: Demo button doesn't count
- `H`: Holding between rooms is allowed
- `U`: Using Up to cancel Down is allowed
- `S`: Stunning is allowed (pausing to manipulate TimeActive, usually done to keep spinners or other hazards unloaded)
- `F`: Freeze is allowed (waiting 115 hours to stop TimeActive from advancing, usually done to keep spinners or other hazards unloaded)

The ruleset with no letters is called `none`, and `DHUSF` is also sometimes called `every`.

However, this doesn't mean we have 32 different versions of each file. In a full-game run we prioritize using the most restrictive possible ruleset for each level over saving time. For example, if in an Any% HUS run 3A can be completed using only HU, then we won't use stunning, even if it saves time, and thus a `3A-MD-HUS.tas` file won't exist.

We also only start a down press in a level when it becomes necessary and end it when it stops being necessary, even if holding it for longer would save time.

## Progress
Currently we are working on an Any% HUS TAS, which will have 2 down presses in total. This involves the following files:
- [x] `0 - Prologue-MD-none.tas` (0x)
- [x] `1A-MD-none.tas` (0x)
- [x] `2A-MD-HU.tas` (1x, hold into 3A)
- [x] `3A-MD-HU.tas` (0.5x, hold into 4A)
- [x] `4A-MD-HU.tas` (0.5x, hold into 5A)
- [x] `5Cassette-MD-HUS.tas` (0.5x, release)
- [x] `5B-MD-HU.tas` (1x, hold into 6A)
- [ ] (WIP) `6A-MD-HU.tas` (0.5x, release)
- [ ] `7A-MD-none.tas` (0x)
