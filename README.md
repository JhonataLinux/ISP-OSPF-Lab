# ISP OSF Lab

## Topologia
Simulação de backbone ISP com redundância entre provedores.

## Provedores
- Umtelecom
- Linkseven
- i7telecom

---

## Endereçamento

### Linkseven

| Link | Rede |
|---|---|
| Borda ↔ R1 | 100.64.254.0/30 |
| Borda ↔ R2 | 100.64.254.4/30 |
| R1 ↔ R3 | 100.64.254.8/30 |
| R2 ↔ R3 | 100.64.254.12/30 |

---

### I7telecom+

| Link | Rede |
|---|---|
| Borda ↔ R1 | 100.90.0.0/30 |
| Borda ↔ R2 | 100.90.0.4/30 |
| R1 ↔ R3 | 100.90.0.8/30 |
| R2 ↔ R3 | 100.90.0.12/30 |

---

## Loopbacks

| Equipamento | IP |
|---|---|
| borda | 100.64.100.0 |
| R1 | 100.64.100.1 |
| R2 | 100.64.100.2 |
| R3 | 100.64.100.3 |


## Tecnologias
- OSPF
- ECMP
- VLAN
- Failover
