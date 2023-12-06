# Jarkom-D25-modul-4

| **No** | **Nama** | **NRP** | 
| ------------- | ------------- | --------- |
| 1 | Andrian Tambunan  | 5025211018 | 
| 2 | Sandhika Surya Ardyanto | 5025211022 |

## Subnetting
![image](https://github.com/AndrianTambunan/Jarkom-D25-modul-4/assets/100081922/8ecdcd98-0835-4f92-a595-eeed1bebcc9b)

| Subnet | Rute | Jumlah IP | Netmask |
| -------- | ------ | --------- | -------- |
| A1 | Heiter-Switch2-Sein&RiegelCanyon | 512 | /22 |
| A2 | Lawine&Heiter-Switch1-BredtRegion | 31 | /26 | 
| A3 | Linie-Switch0-GranzChannel | 255 | /23 |
| A4 | Lawine-Linie | 2 | /30 |
| A5 | Linie-Eisen | 2 | /30 |
| A6 | Eisen-Switch3-Richter&Revolt | 3 | /29 |
| A7 | Lugner-Switch4-GrobeForest | 251 | /24 |
| A8 | Lugner-Switch5-TurkRegion | 1001 | /22 |
| A9 | Lugner-Eisen | 2 | /30 |
| A10 | Eisen-Switch12-Stark | 2 | /30 |
| A11 | Denken-Switch10-RoyalCapital&WilleRegion | 127 | /24 | 
| A12 | Denken-Aura | 2 | /30 |
| A13 | Frieren-Aura | 2 | /30 | 
| A14 | Fern-Switch8-AppetitRegion&LaubHills | 1023 | /21 |
| A15 | Flamme-Switch7-RohrRoad | 1001 | /22 |
| A16 | Himmel-Switch11-SchwerMountains | 6 | /29 |
| A17 | Himmel-Flamme | 2 | /30 |
| A18 | Flamme-Frieren | 2 | /30 |
| A19 | Fern-Flamme | 2 | /30 |
| A20 | Frieren-Switch6-LakeKorridor | 25 | /27 |
| A21 | Eisen-Aura | 2 | /30 |

## VLSM CPT
### Tree VLSM
![Mod4 drawio](https://github.com/AndrianTambunan/Jarkom-D25-modul-4/assets/100081922/cac25ee6-16c1-45c4-9c14-fa71a0929ce6)

### Pembagian IP VLSM
| Subnet | Network ID	| Netmask | Broadcast |
| -------- | ------ | --------- | -------- |
| A1	| 10.34.0.0	|	255.255.252.0	| 10.34.3.255 |
| A2	| 10.34.24.0	|	255.255.255.192	| 10.34.24.63 |
| A3	| 10.34.16.0	|	255.255.254.0	| 10.34.17.255 |
| A4	| 10.34.24.112	|	255.255.255.252	| 10.34.24.115 |
| A5	| 10.34.34.116	|	255.255.255.252	| 10.34.34.119 |
| A6	| 10.34.24.10	|	255.255.255.252	| 10.34.24.17 |
| A7	| 10.34.17.0	|	255.255.255.0	| 10.34.17.255 |
| A8	| 10.34.4.0	|	255.255.252.0	| 10.34.7.255 |
| A9	| 10.34.24.120	|	255.255.255.252	| 10.34.24.123 |
| A10	| 10.34.24.124	|	255.255.255.252	| 10.34.24.127 |
| A11	| 10.34.16.0	|	255.255.255.0	| 10.34.16.255 |
| A12	| 10.34.24.128	|	255.255.255.252	| 10.34.24.131 |
| A13	| 10.34.24.132	|	255.255.255.252	| 10.34.24.135 |
| A14	| 10.34.8.0	|	255.255.248.0	| 10.34.15.255 |
| A15	| 10.34.20.0	|	255.255.252.0	| 10.34.23.255 |
| A16	| 10.34.24.96	|	255.255.255.252	| 10.34.24.103 |
| A17	| 10.34.24.136	|	255.255.255.248	| 10.34.24.139 |
| A18	| 10.34.24.140	|	255.255.255.252	| 10.34.24.143 |
| A19	| 10.34.24.144	|	255.255.255.252	| 10.34.24.147 |
| A20	| 10.34.24.64	|	255.255.255.224	| 10.34.24.96 |
| A21	| 10.34.24.148	|	255.255.255.252	| 10.34.24.151 |

### IP Configuration VLSM
---
- Heiter (A1)
```
IPv4 Address  : 10.34.0.1
Subnet Mask   : 255.255.252.0
```

- Sien (A1)
```
Default Gateaway  : 10.34.0.1
IPv4 Address      : 10.34.0.2
Subnet Mask       : 255.255.252.0
```

- RiegelCanyon (A1)
```
Default Gateaway  : 10.34.0.1
IPv4 Address      : 10.34.0.3
Subnet Mask       : 255.255.252.0
```
---

- Heiter (A2)
```
IPv4 Address  : 10.34.24.2
Subnet Mask   : 255.255.255.192
```

- Lawine (A2)
```
IPv4 Address  : 10.34.24.1
Subnet Mask   : 255.255.255.192
```

- BredtRegion (A2)
```
Default Gateaway  : 10.34.24.1
IPv4 Address      : 10.34.24.3
Subnet Mask       : 255.255.255.192
```
---

- Linie (A3)
```
IPv4 Address  : 10.34.18.1
Subnet Mask   : 255.255.254.0
```

- GranzChannel (A3)
```
Default Gateaway  : 10.34.18.1
IPv4 Address      : 10.34.18.2
Subnet Mask       : 255.255.254.0
```
---

- Linie (A4)
```
IPv4 Address  : 10.34.24.113
Subnet Mask   : 255.255.255.252
```

- Lawine (A4)
```
IPv4 Address  : 10.34.24.114
Subnet Mask   : 255.255.255.252
```
---

- Linie (A5)
```
IPv4 Address  : 10.34.24.118
Subnet Mask   : 255.255.255.252
```

- Eisen (A5)
```
IPv4 Address  : 10.34.24.117
Subnet Mask   : 255.255.255.252
```
---

- Eisen (A6)
```
IPv4 Address  : 10.34.24.105
Subnet Mask   : 255.255.255.248
```

- Richter (A6)
```
Default Gateaway  : 10.34.24.105
IPv4 Address      : 10.34.24.106
Subnet Mask       : 255.255.255.248
```

- Revolt (A6)
```
Default Gateaway  : 10.34.24.105
IPv4 Address      : 10.34.24.107
Subnet Mask       : 255.255.255.248
```
---

- Lugner (A7)
```
IPv4 Address  : 10.34.17.1
Subnet Mask   : 255.255.255.0
```

- GrobeForest (A7)
```
Default Gateaway  : 10.34.17.1
IPv4 Address      : 10.34.17.2
Subnet Mask       : 255.255.255.0
```
---

- Lugner (A8)
```
IPv4 Address  : 10.34.4.1
Subnet Mask   : 255.255.252.0
```

- TurkRegion (A8)
```
Default Gateaway  : 10.34.4.1
IPv4 Address      : 10.34.4.2
Subnet Mask       : 255.255.252.0
```
---

- Lugner (A9)
```
IPv4 Address  : 10.34.24.122
Subnet Mask   : 255.255.255.252
```

- Eisen (A9)
```
IPv4 Address  : 10.34.24.121
Subnet Mask   : 255.255.255.252
```
---

- Eiseb (A10)
```
IPv4 Address  : 10.34.24.125
Subnet Mask   : 255.255.252.0
```

- Stark (A10)
```
Default Gateaway  : 10.34.24.125
IPv4 Address      : 10.34.24.126
Subnet Mask       : 255.255.252.0
```
---

- Denken (A11)
```
IPv4 Address  : 10.34.16.1
Subnet Mask   : 255.255.255.0
```

- RoyalCapital (A11)
```
Default Gateaway  : 10.34.16.1
IPv4 Address      : 10.34.16.2
Subnet Mask       : 255.255.255.0
```

- WilleRegion (A11)
```
Default Gateaway  : 10.34.16.1
IPv4 Address      : 10.34.16.65
Subnet Mask       : 255.255.255.0
```
---

- Aura (A12)
```
IPv4 Address  : 10.34.24.129
Subnet Mask   : 255.255.255.252
```

- Denken (A12)
```
IPv4 Address  : 10.34.24.130
Subnet Mask   : 255.255.255.252
```
---

- Aura (A13)
```
IPv4 Address  : 10.34.24.133
Subnet Mask   : 255.255.255.252
```

- Frieren (A13)
```
IPv4 Address  : 10.34.24.134
Subnet Mask   : 255.255.255.252
```
---

- Fern (A14)
```
IPv4 Address  : 10.34.8.1
Subnet Mask   : 255.255.248.0
```

- AppetitRegion (A14)
```
Default Gateaway  : 10.34.8.1
IPv4 Address      : 10.34.9.142
Subnet Mask       : 255.255.248.0
```

- LaubHills (A14)
```
Default Gateaway  : 10.34.8.1
IPv4 Address      : 10.34.8.2
Subnet Mask       : 255.255.248.0
```
---

- Flamme (A15)
```
IPv4 Address  : 10.34.20.1
Subnet Mask   : 255.255.252.0
```

- RohrRoad (A15)
```
Default Gateaway  : 10.34.20.1
IPv4 Address      : 10.34.20.2
Subnet Mask       : 255.255.252.0
```
---

- Himmel (A16)
```
IPv4 Address  : 10.34.25.97
Subnet Mask   : 255.255.255.248
```

- SchwerMountains (A16)
```
Default Gateaway  : 10.34.25.97
IPv4 Address      : 10.34.25.98
Subnet Mask       : 255.255.255.248
```
---

- Flamme (A17)
```
IPv4 Address  : 10.34.24.137
Subnet Mask   : 255.255.255.252
```

- Himmel (A17)
```
IPv4 Address  : 10.34.24.138
Subnet Mask   : 255.255.255.252
```
---

- Flamme (A18)
```
IPv4 Address  : 10.34.24.142
Subnet Mask   : 255.255.255.252
```

- Frieren (A18)
```
IPv4 Address  : 10.34.24.141
Subnet Mask   : 255.255.255.252
```
---

- Flamme (A19)
```
IPv4 Address  : 10.34.24.145
Subnet Mask   : 255.255.255.252
```

- Fern (A19)
```
IPv4 Address  : 10.34.24.146
Subnet Mask   : 255.255.255.252
```
---

- Frieren (A20)
```
IPv4 Address  : 10.34.24.65
Subnet Mask   : 255.255.255.224
```

- LakeKorridor (A20)
```
Default Gateaway  : 10.34.24.65
IPv4 Address      : 10.34.24.66
Subnet Mask       : 255.255.255.224
```
---

- Aura (A21)
```
IPv4 Address  : 10.34.24.149
Subnet Mask   : 255.255.255.252
```

- Eisen (A21)
```
IPv4 Address  : 10.34.24.150
Subnet Mask   : 255.255.255.252
```
---
## Routing VLSM
- Heiter
```
0.0.0.0/0 via 10.34.24.1
```
- Lawine
```
0.0.0.0/0 via 10.34.24.113
10.34.24.0/26 via 10.34.24.2
10.34.24.0/26 via 10.34.24.2
```
- Linie
```
10.34.24.112/30 via 10.34.24.114
10.34.24.0/26 via 10.34.24.114
10.34.0.0/22 via 10.34.24.114
0.0.0.0/0 via 10.34.24.117
```
- Eisen
```
10.34.17.0/24 via 10.34.24.122
10.34.4.0/22 via 10.34.24.122
0.0.0.0/0 via 10.34.24.149
10.34.0.0/22 via 10.34.24.118
10.34.24.0/26 via 10.34.24.118
```
- Lugner
```
0.0.0.0/0 via 10.34.24.121
```
- Denken
```
0.0.0.0/0 via 10.34.24.129
```
- Frieren
```
0.0.0.0/0 via 10.34.25.133
10.34.8.0/21 via 10.34.24.142
10.34.24.144/30 via 10.34.24.142
10.34.24.140/30 via 10.34.24.142
10.34.20.0/22 via 10.34.24.142
10.34.24.136/30 via 10.34.24.142
10.34.24.96/29 via 10.34.24.142
```
- Flamme
```
0.0.0.0/0 via 10.34.24.141
10.34.8.0/21 via 10.34.24.146
10.34.24.144/30 via 10.34.24.146
10.34.24.96/29 via 10.34.24.138
10.34.24.136/30 via 10.34.24.138
```
- Himmel
```
0.0.0.0/0 via 10.34.24.137
```
- Fern
```
0.0.0.0/0 via 10.34.24.145
```
- Aura
```
10.34.24.128/30 via 10.34.24.130
10.34.16.0/24 via 10.34.24.130
10.34.24.132/30 via 10.34.24.134
10.34.24.64/27 via 10.34.24.134
10.34.24.140/30 via 10.34.24.134
10.34.24.144/30 via 10.34.24.134
10.34.8.0/21 via 10.34.24.134
10.34.24.136/30 via 10.34.24.134
10.34.20.0/22 via 10.34.24.134
10.34.24.96/29 via 10.34.24.134
10.34.24.124/30 via 10.34.24.150
10.34.24.104/29 via 10.34.24.150
10.34.24.120/30 via 10.34.24.150
10.34.4.0/22 via 10.34.24.150
10.34.17.0/24 via 10.34.24.150
10.34.24.116/30 via 10.34.24.150
10.34.18.0/23 via 10.34.24.150
10.34.24.112/30 via 10.34.24.150
10.34.24.0/26 via 10.34.24.150
10.34.0.0/22 via 10.34.24.150
10.34.24.148/30 via 10.34.24.150
```



## CIDR GNS 3
### GNS 3 Topologi
### Flow Pembagian CIDR
### Pembagian Blok Subnet
| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| A1 | /22 | A2 | /26 | B1 | /21 |
| A8 | /22 | A7 | /24 | B2 | /21 |
| A14 | /21 | A19 | /30 | B3 | /20 |
| A16 | /29 | A17 | /30 | B4 | /28 | 
| A11 | /24 | A12 | /30 | B5 | /23 |


| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| B1 | /21 | A4 | /30 | C1 | /20 |
| B2 | /21 | A9 | /30 | C2 | /20 |
| A15 | /22 | B4 | /28 | C3 | /21 |


| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| C1 | /20 | A3 | /23 | D1 | /19 |
| C2 | /20 | A10 | /30 | D2 | /19 |
| B3 | /20 | C3 | /21 | D3 | /19 |


| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| D1 | /19 | A5 | /30 | E1 | /18 |
| D2 | /19 | A6 | /29 | E2 | /18 |
| D3 | /19 | A18 | /30 | E3 | /18 |

| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| E1 | /18 | E2 | /18 | F1 | /17 |
| E3 | /18 | A20 | /27 | F2 | /17 |

| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| F1 | /17 | A21 | /30 | G1 | /16 |
| F2 | /17 | A13 | /30 | G2 | /16 |

| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| G1 | /16 | G2 | /16 | H1 | /15 |

| Subnet 1 | Netmask 1 | Subnet 2 | Neetmask 2 | Blok Subnet | Netmask Blok |
| ----------- | ----------- | ------------ | ----------- | ----------- | ------------ |
| H1 | /15 | B5 | /23 | I1 | /14 |

### Tree
### Pembagian IP
### IP Configuration
- Aura
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.34.1.1
	netmask 255.255.255.252

auto eth2
iface eth1 inet static
	address 10.35.128.1
	netmask 255.255.255.252

auto eth3
iface eth1 inet static
	address 10.34.128.1
	netmask 255.255.255.252
```
- Denken
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.36.1.2
	netmask 255.255.255.252
	gateway 10.36.1.1

auto eth1
iface eth1 inet static
	address 10.36.0.1
	netmask 255.255.255.0
```
- RoyalCapital
```
auto eth0
iface eth0 inet static
	address 10.34.0.2
	netmask 255.255.255.0
	gateway 10.34.0.1
```
- WilleRegion
```
auto eth0
iface eth0 inet static
	address 10.34.0.3
	netmask 255.255.255.0
	gateway 10.34.0.1
```
- l
### Percobaan Ping IP (per Subnet CIDR)
### Kendala Pengerjaan
