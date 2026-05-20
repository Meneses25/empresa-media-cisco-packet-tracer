# 🏢 Empresa Média (Cisco Packet Tracer)

## 🎯 Objetivo
Simular uma infraestrutura corporativa com múltiplos setores, segmentação de rede, serviços internos e mecanismos de segurança.

---

# 🧩 Topologia

## 🔹 Infraestrutura
- 2 Roteadores
- 3 Switches
- PCs e Notebooks
- Servidor DNS/Web
- NAT Simulado

---

# 🌐 VLANs

| VLAN | Setor | Rede |
|---|---|---|
| 10 | TI | 192.168.10.0/24 |
| 20 | RH | 192.168.20.0/24 |
| 30 | Financeiro | 192.168.30.0/24 |
| 40 | Recepção | 192.168.40.0/24 |
| 50 | Voz | 192.168.50.0/24 |

---

# ⚙️ Tecnologias Utilizadas

## 🔹 Switching
- VLAN
- Trunk
- Voice VLAN
- Port Security
- Hardening

## 🔹 Routing
- Inter-VLAN Routing
- Router-on-a-Stick
- NAT

## 🔹 Serviços
- DHCP
- DNS
- HTTP Server

## 🔹 Segurança
- ACL
- Firewall Interno
- SSH Seguro
- Restrição Administrativa

---

# 🔐 Segurança Implementada

## ✅ ACL
- Bloqueio da VLAN Recepção para a VLAN Financeiro

## ✅ SSH Restrito
- Apenas a VLAN TI pode administrar os roteadores

## ✅ Port Security
- Controle de MAC Address nas portas de acesso

## ✅ Hardening
- Portas não utilizadas desativadas
- VLAN 999 para portas ociosas

---

# 🧪 Testes Realizados

| Teste | Resultado |
|---|---|
| Comunicação entre VLANs | ✅ |
| DHCP funcional | ✅ |
| NAT funcional | ✅ |
| DNS interno funcional | ✅ |
| HTTP interno funcional | ✅ |
| ACL funcionando | ✅ |
| SSH restrito funcionando | ✅ |

---



# 🚀 Status do Projeto

✅ Concluído
