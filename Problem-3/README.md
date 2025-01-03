## Addressing Table

| Device | Interface | IP Address     | Subnet Mask     | Default Gateway |
|--------|-----------|----------------|-----------------|-----------------|
| HQ     | S0/0/0    | 10.0.0.1       | 255.255.255.252 | N/A             |
|        | S0/0/1    | 10.0.0.5       | 255.255.255.252 | N/A             |
|        | Fa0/0     | 192.168.64.1   | 255.255.255.0   | N/A             |
|        | Fa0/1     | 192.168.65.1   | 255.255.255.0   | N/A             |
| B1     | S0/0/0    | 10.0.0.2       | 255.255.255.252 | N/A             |
|        | Fa0/0     | 172.24.0.1     | 255.255.0.0     | N/A             |
|        | Fa0/1     | 172.25.0.1     | 255.255.0.0     | N/A             |
|        | Fa1/0     | 172.26.0.1     | 255.255.0.0     | N/A             |
|        | Fa1/1     | 172.27.0.1     | 255.255.0.0     | N/A             |
| B2     | S0/0/0    | 10.0.0.6       | 255.255.255.252 | N/A             |
|        | Fa0/0     | 192.168.0.1    | 255.255.255.0   | N/A             |
|        | Fa0/1     | 192.168.1.1    | 255.255.255.0   | N/A             |
|        | Fa1/0     | 192.168.2.1    | 255.255.255.0   | N/A             |
|        | Fa1/1     | 192.168.3.1    | 255.255.255.0   | N/A             |
| PC1    | NIC       | 172.24.0.10    | 255.255.0.0     | 172.24.0.1      |
| PC2    | NIC       | 172.24.1.10    | 255.255.0.0     | 172.25.0.1      |
| PC3    | NIC       | 172.24.2.10    | 255.255.0.0     | 172.26.0.1      |
| PC4    | NIC       | 172.24.3.10    | 255.255.0.0     | 172.27.0.1      |
| PC5    | NIC       | 192.168.64.10  | 255.255.255.0   | 192.168.64.1    |
| PC6    | NIC       | 192.168.65.10  | 255.255.255.0   | 192.168.65.1    |
| PC7    | NIC       | 192.168.0.10   | 255.255.255.0   | 192.168.0.1     |
| PC8    | NIC       | 192.168.1.10   | 255.255.255.0   | 192.168.1.1     |
| PC9    | NIC       | 192.168.2.10   | 255.255.255.0   | 192.168.2.1     |
| PC10   | NIC       | 192.168.3.10   | 255.255.255.0   | 192.168.3.1     |
