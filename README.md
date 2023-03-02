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
| Switch      | SW     |
| Router      | RT     |
| Workstation | WS     |
| Acess Point | AP     |
| Server      | SR     |

### Aufbau

{Namenskürzel}{Nummerierung von 001-999}

## Geräte

### Workstations

| Gerät       | Hostname | IP              |
| ----------- | -------- | --------------- |
| Basils VM   | WS001    | 192.168.222.100 |
| Michis VM   | WS002    | 192.168.222.101 |
| Luans VM    | WS003    | 192.168.222.102 |
| Iljas VM    | WS004    | 192.168.222.103 |
| Avis VM     | WS005    | 192.168.222.104 |
| Eddys VM    | WS006    | 192.168.222.105 |
| Flos VM     | WS007    | 192.168.222.106 |
| Enriques VM | WS008    | 192.168.222.107 |
| Karmas VM   | WS009    | 192.168.222.108 |
| Arlinds VM  | WS010    | 192.168.223.100 |
| Rayans VM   | WS011    | 192.168.223.101 |
| Haruns VM   | WS012    | 192.168.223.102 |
| Kim VM      | WS013    | 192.168.223.103 |
| Robin VM    | WS014    | 192.168.223.104 |
| Mika VM     | WS015    | 192.168.223.105 |
| Nathan VM   | WS016    | 192.168.223.106 |
| Rijha VM    | WS017    | 192.168.223.107 |


### Switches

| IP             | Hostname |
| -------------- | -------- |
| 192.168.222.10 | SW001    |
| 192.168.222.11 | SW002    |
| 192.168.223.10 | SW003    |
| 192.168.223.11 | SW004    |

### Routers

| IP            | Hostname    |
| ------------- | ----------- |
| 192.168.22.1  | Core-Router |
| 192.168.222.1 | RT001       |
| 192.168.223.1 | RT002       |

### Access Points

| IP             | Hostname |
| -------------- | -------- |
| 192.168.222.20 | AP001    |

### Servers

| IP              | Hostname |
| --------------- | -------- |
| 192.168.222.200 | SR001    |

## DHCP Config

### DHCP Subnet 192.168.222.0/24

![dhcp-config-222](dhcp-config-222.png)

### DHCP Subnet 192.168.223.0/24

![WIP]()

## Netzwerkplan

![Netzwerkplan](Netzwerkplan.png)
