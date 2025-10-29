## Custom server for NHL 10

- Community Discord: https://discord.com/invite/dsAz2g9S8v
- RPCS3 Wiki: https://wiki.rpcs3.net/index.php?title=NHL_10

## Project Structure
### Zamboni
  - A C# Server Program, that responds to client requests
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
### Website
  - Website hosted in https://zamboni.gg/
  - Displays server status
  - Displays statistics about played games from yet not open source api
    
## Credits and Resources

- [BlazeSDK](https://github.com/Aim4kill/BlazeSDK) By [@Aim4kill](https://github.com/Aim4kill)
- [ME3PSE](https://github.com/PrivateServerEmulator/ME3PSE) By [@WarrantyVoider](https://github.com/zeroKilo) [@Erik-JS](https://github.com/Erik-JS)
- [BFP4FToolsWV](https://github.com/zeroKilo/BFP4FToolsWV) & [BFP4FToolsWV Wiki](https://github.com/zeroKilo/BFP4FToolsWV/wiki) By [@WarrantyVoider](https://github.com/zeroKilo)
- [PocketRelay](https://github.com/PocketRelay) & [jacobtread/tdf](https://github.com/jacobtread/tdf) By [@jacobtread](https://github.com/jacobtread/)
- [Hall of Meat](https://github.com/hallofmeat) By [@Hall of Meat Team](https://github.com/hallofmeat)
- [BlazeServer](https://github.com/pedromartins1/BlazeServer) By [@Perdo Martins](https://github.com/pedromartins1)
- [BlazeSharkExtended](https://github.com/Tratos/BlazeSharkExtended) By [@Tratos](https://github.com/Tratos)
- [recap_server](https://github.com/vitor251093/recap_server) By [@vitor251093](https://github.com/vitor251093) and [@dalkon](https://github.com/dalkon)
- [openBlase](https://github.com/openBlase/openBlase) By [@openBlase](https://github.com/openBlase/openBlase)
- [BF4BlazeEmulator](https://github.com/buchacho/BF4BlazeEmulator) By [@buchacho](https://github.com/buchacho)
- [@the1Domo](https://github.com/g91)
