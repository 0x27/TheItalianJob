# TheItalianJob
Uses Shodan to locate HackingTeam C&C Servers.

Only releasing the fingerprints because they are burned to the fucking ground now. Fuck those HackingTeam Scumlords. It now returns no valid results due to C&C server shutdown, but releasing for historical reasons.

Greetz to Phineas Fisher, you fucking hero.

![Fuck HackingTeam](https://raw.githubusercontent.com/0x27/TheItalianJob/master/screenshot.jpg)

Licence: WTFPL.

More fingerprints to add now that their sekret sauce is public thanks to our lord and saviour. If you go looking at other state surveillance malwares though, you can fingerprint their C&C servers just as easily. Most of them use either a wierdly configured webserver, or a fake webserver that presents a particular banner as the C&C service. Hence, are easy to locate via shodan or by zmapping the internet.

Requirements: Shodan python module, Shodan API key from [Shodan, obviously](https://shodan.io)
```
pip install shodan
```

Examples of past C&C servers...
```
106.187.88.154
106.187.93.203
108.161.130.88
108.166.112.17
109.235.193.83
124.217.238.91
124.217.245.26
14.136.236.147
14.136.236.163
14.136.236.165
158.255.215.87
173.230.130.68
173.230.137.84
173.255.212.72
176.58.102.128
176.58.102.218
176.58.121.242
178.79.159.242
184.106.244.36
184.75.250.118
189.177.47.222
192.30.161.219
193.232.60.238
198.101.232.37
198.101.232.81
198.136.60.208
198.58.101.251
202.157.184.22
209.140.24.194
209.140.24.195
209.140.24.196
216.118.249.92
216.224.174.48
217.29.123.184
41.248.248.181
41.248.248.183
46.166.162.138
46.166.162.148
46.166.163.179
46.183.220.222
46.251.239.122
46.251.239.125
46.251.239.130
46.251.239.131
62.251.188.193
65.111.180.124
65.111.181.108
69.164.222.128
79.172.249.110
91.148.168.162
95.228.202.101
95.228.202.104
95.228.202.108
95.228.202.114
95.228.202.120
```
