# Network Monitoring Infrastructure Task, 27.02.2023

## Team

### 27.02-28.02 PLA 1

Basil, Luan, Michael, Edlir, Avinash, Ilja, Florin, Enrique, Karma

### 1.03 PLA 1 & PLA 2

Basil, Luan, Michael, Edlir, Avinash, Ilja, Florin, Enrique, Karma, Robin, Mika, Kim, Harun, Arlind, Ryan, Rijha, Nathan

### 02.03-03.03 PLA 2

Robin, Mika, Kim, Harun, Arlind, Ryan, Rijha, Nathan + Karma, Enrique Florin

## Namenskonvention

| Gerät       | Kürzel |
| ----------- | ------ |
| Switch      | sw     |
| Router      | rt     |
| Workstation | ws     |
| Acess Point | ap     |
| Server      | sr     |

### Aufbau

{Namenskürzel}{Nummerierung von 001-999}

## Geräte

### Workstations

| Gerät       | Hostname | IP                     |
| ----------- | -------- | ---------------------- |
| Basils VM   | ws001    | 192.168.22**2**.100/24 |
| Michis VM   | ws002    | 192.168.22**2**.101/24 |
| Luans VM    | ws003    | 192.168.22**2**.102/24 |
| Iljas VM    | ws004    | 192.168.22**2**.103/24 |
| Avis VM     | ws005    | 192.168.22**2**.104/24 |
| Edlirs VM   | ws006    | 192.168.22**2**.105/24 |
| Flos VM     | ws007    | 192.168.22**2**.106/24 |
| Enriques VM | ws008    | 192.168.22**2**.107/24 |
| Karmas VM   | ws009    | 192.168.22**2**.108/24 |
| Arlinds VM  | ws010    | 192.168.22**3**.100/24 |
| Rayans VM   | ws011    | 192.168.22**3**.101/24 |
| Haruns VM   | ws012    | 192.168.22**3**.102/24 |
| Kim VM      | ws013    | 192.168.22**3**.103/24 |
| Robin VM    | ws014    | 192.168.22**3**.104/24 |
| Mika VM     | ws015    | 192.168.22**3**.105/24 |
| Nathan VM   | ws016    | 192.168.22**3**.106/24 |
| Rijha VM    | ws017    | 192.168.22**3**.107/24 |

### Switches

| IP             | Hostname |
| -------------- | -------- |
| 192.168.222.10 | sw001    |
| 192.168.222.11 | sw002    |
| 192.168.223.10 | sw003    |
| 192.168.223.11 | sw004    |

### Routers

| IP            | Hostname           |
| ------------- | ------------------ |
| 192.168.219.1 | core-router (OPT1) |
| 10.80.4.244   | core-router (WAN)  |
| 192.168.220.1 | core-router (LAN)  |
| 192.168.222.1 | rt001              |
| 192.168.223.1 | rt002              |

### Access Points

| IP             | Hostname |
| -------------- | -------- |
| 192.168.222.20 | ap001    |
| 192.168.223.20 | ap002    |

### Servers

| IP              | Hostname |
| --------------- | -------- |
| 192.168.222.200 | sr001    |

## DHCP Config

### DHCP Subnet 192.168.222.0/24

![dhcp-config-222](dhcp-config-222.png)

### DHCP Subnet 192.168.223.0/24

## Netzwerkplan

![Netzwerkplan](networkplan-filius.jpg)
