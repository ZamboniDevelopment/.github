## Custom servers for NHL Games, Currently playable only in RPCS3!

- Community [Discord](https://zamboni.gg/discord)

## Project Structure
### Zamboni
  - A C# Server Program, that responds to client requests for NHL 10 clients
### Zamboni11
  - A C# Server Program, that responds to client requests for NHL 11 clients
### Zamboni3
  - A C# Server Program, that responds to client requests for NHL 12-Legacy clients
### ZamboniUltimateTeam
  - Subproject implementing ultimate team features
### ZamboniCommonComponents
  - Subproject implementing NHL specific components
### TheDirector
  - A Separate redirector instance.
  - Redirecting clients to the right servers
  - Needed because games listen on the same redirector port
### BlazeSDK
  - SDK (a Framework) made by [@Aim4kill](https://github.com/Aim4kill)
  - Used by Zamboni to respond to client using a said protocol
  - Minor changes made to it to make it compatible
### Skateboard3Server.Qos
  - A QoS Server made by [@Hall of Meat Team](https://github.com/hallofmeat)
  - A server responding to client with minimal QoS data, which is needed by the client
  - Minor changes made to it to make it compatible
### ppu-patches
  - Game patches in PowerPC assembly, in rpcs3 patching format.
  - Game patches need to be applied for the game to be played online
  - Needed for the time being, because the server is not a perfect 1:1 to original
### [Website](https://zamboni.gg/)
  - Displays server status and statistics about played games
  - Maintained by [@dtzdev](https://github.com/dtzdev)
### [Zamboni-League](https://zamboni.gg/league)
  - Visualizes currently ongoing league teams/statistics/results
  - [Repository](https://github.com/jfmartineau45/zamboni-league) Maintained by [@jfmartineau45](https://github.com/jfmartineau45)
### DiscordBot
  - A polling bot displaying server status
## Credits and Resources

- [BlazeSDK](https://github.com/Aim4kill/BlazeSDK) & [SceNetNp](https://github.com/Aim4kill/PSN) & [ProtoSSL Bug](https://github.com/Aim4kill/Bug_OldProtoSSL) By [@Aim4kill](https://github.com/Aim4kill)
- [ME3PSE](https://github.com/PrivateServerEmulator/ME3PSE) By [@WarrantyVoider](https://github.com/zeroKilo) [@Erik-JS](https://github.com/Erik-JS)
- [BFP4FToolsWV](https://github.com/zeroKilo/BFP4FToolsWV) & [BFP4FToolsWV Wiki](https://github.com/zeroKilo/BFP4FToolsWV/wiki) By [@WarrantyVoider](https://github.com/zeroKilo)
- [PocketRelay](https://github.com/PocketRelay) & [jacobtread/tdf](https://github.com/jacobtread/tdf) By [@jacobtread](https://github.com/jacobtread/)
- [Hall of Meat](https://github.com/hallofmeat) By [@Hall of Meat Team](https://github.com/hallofmeat)
- [BlazeServer](https://github.com/pedromartins1/BlazeServer) By [@Perdo Martins](https://github.com/pedromartins1)
- [BlazeSharkExtended](https://github.com/Tratos/BlazeSharkExtended) By [@Tratos](https://github.com/Tratos)
- [recap_server](https://github.com/vitor251093/recap_server) By [@vitor251093](https://github.com/vitor251093) and [@dalkon](https://github.com/dalkon)
- [openBlase](https://github.com/openBlase/openBlase) By [@openBlase](https://github.com/openBlase/openBlase)
- [BF4BlazeEmulator](https://github.com/buchacho/BF4BlazeEmulator) By [@buchacho](https://github.com/buchacho)
- [Skate3BlazeServer](https://github.com/skate6743/Skate3BlazeServer) By [@Wispp](https://github.com/skate6743)
- [@the1Domo](https://github.com/g91)
