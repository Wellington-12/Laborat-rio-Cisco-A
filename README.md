# Laboratório Cisco — Switching, Router e SSH

Laboratório desenvolvido no **Cisco Packet Tracer** para prática de conceitos de **Redes de Computadores e Infraestrutura Cisco**.

O cenário foi baseado no projeto de estudos do **Robson Vaamonde**, utilizado como referência para aprendizado e prática:

[Projeto original — Infra Cisco / Cenário A](https://github.com/vaamonde/infra-cisco/tree/main/02-project/01-cenario-A?utm_source=chatgpt.com)

## 🛠️ Configurações realizadas

* Configuração básica de **Switch Cisco 2960**
* Configuração de **Switching e conectividade LAN**
* Configuração de **SVI para gerenciamento**
* Configuração de **VTY**
* Configuração de **SSH para acesso remoto**
* Configuração básica do **Router Cisco 1941**
* Configuração da **interface LAN IPv4**
* Configuração do **DNS Server**
* **Backup e Restore** da configuração do Cisco IOS
* Testes de conectividade com `ping` e comandos `show`

## 🌐 Topologia

Rede principal utilizada:

```text
192.168.1.0/24
```

Principais endereços:

```text
Router/Gateway: 192.168.1.254
Server/DNS:     192.168.1.1
Switch1 SVI:    192.168.1.250
Switch2 SVI:    192.168.1.251
```

## 🎯 Objetivo

O objetivo foi transformar conceitos teóricos em prática, desenvolvendo conhecimentos aplicáveis a ambientes de **Infraestrutura, Redes e NOC**, incluindo configuração, gerenciamento remoto, conectividade e recuperação de configurações Cisco.

**Ferramenta:** Cisco Packet Tracer
**Status:** ✅ Laboratório concluído
