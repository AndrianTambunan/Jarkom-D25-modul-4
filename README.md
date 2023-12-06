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
### Pembagian IP VLSM
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


- Heiter (A1)
```
IPv4 Address  : 10.34.24.2
Subnet Mask   : 255.255.255.192
```

- Lawine (A1)
```
IPv4 Address  : 10.34.24.2
Subnet Mask   : 255.255.255.192
```

- BredtRegion (A1)
```
Default Gateaway  : 10.34.0.1
IPv4 Address      : 10.34.0.2
Subnet Mask       : 255.255.252.0
```

- Sien (A1)
```
Default Gateaway  : 10.34.0.1
IPv4 Address      : 10.34.0.2
Subnet Mask       : 255.255.252.0
```
---
## Routing VLSM



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
### Percobaan Ping IP (per Subnet CIDR)
### Kendala Pengerjaan
