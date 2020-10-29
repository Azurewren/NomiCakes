# NomiCakes
This is a fork of the World of Warcraft addon from [semlar/NomiCakes](https://pages.github.com/semlar/NomiCakes) which is found on (https://www.curseforge.com/wow/addons/nomicakes) for the purposes of updating it to version 9.0.0.1 (Shadowlands) and fixing some bugs.

### Changes:
- Added local function **GossipResize(titleButton)**
- Replaced **_G[buttonName]** with **GossipFrame_GetTitleButton(i)** in DecorateNomi function
- Replaced **_G[buttonName .. 'GossipIcon']** with **GossipFrame_GetTitleButton(i).Icon** in DecorateNomi function
- Replaced **'interface\\gossipframe\\workordergossipicon'** with **'interface/gossipframe/workordergossipicon'**
