A simple minecraft server image based on [itzg's image](https://github.com/itzg/docker-minecraft-server).

# What does it contain?

This image contains an 1.21.5 server with the following mods:

1. [fabric-api](https://modrinth.com/mods/fabric-api)
1. [lithium](https://modrinth.com/mods/lithium)
1. [noisium](https://modrinth.com/mods/noisium)
1. [c2me-fabric](https://modrinth.com/mods/c2me-fabric)
1. [ferrite-core](https://modrinth.com/mods/ferrite-core)
1. [simple-voice-chat](https://modrinth.com/mods/simple-voice-chat)
1. [vanish](https://modrinth.com/mods/vanish)
1. [anti-xray](https://modrinth.com/mods/anti-xray)
1. [viafabric](https://modrinth.com/mods/viafabric)

# How to run it?

Clone the repository and then run the following command inside the repository's folder:

```bash
docker compose up -d
```

*DISCLAIMER*: ports `25565` (for the minecraft server itself) and `24454` (for the voice chat) must be open in order to work properly.
