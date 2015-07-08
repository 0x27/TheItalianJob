# TheItalianJob
Uses Shodan to locate HackingTeam C&C Servers.

Only releasing the fingerprints because they are burned to the fucking ground now. Fuck those HackingTeam Scumlords. It now returns no valid results due to C&C server shutdown, but releasing for historical reasons.

Examples of past C&C servers...
```
124.217.245.26
65.111.181.108
124.217.245.26
65.111.181.108
124.217.245.26
65.111.181.108
```

Greetz to Phineas Fisher, you fucking hero.

![Fuck HackingTeam](https://raw.githubusercontent.com/0x27/TheItalianJob/master/screenshot.jpg)

Licence: WTFPL.

More fingerprints to add now that their sekret sauce is public thanks to our lord and saviour. If you go looking at other state surveillance malwares though, you can fingerprint their C&C servers just as easily. Most of them use either a wierdly configured webserver, or a fake webserver that presents a particular banner as the C&C service. Hence, are easy to locate via shodan or by zmapping the internet.

Requirements: Shodan python module, Shodan API key from [Shodan, obviously](https://shodan.io)
```
pip install shodan
```
