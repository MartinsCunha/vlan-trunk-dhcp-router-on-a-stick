# vlan-trunk-dhcp-NAT-router-on-a-stick
# Configuração de Rede com VLAN, Trunk, DHCP e Router-on-a-Stick

## 📌 Descrição
Este projeto demonstra a implementação de uma rede local segmentada utilizando **VLANs**, comunicação por **links Trunk**, atribuição automática de endereços IP através de **DHCP** e roteamento entre VLANs usando a técnica **Router-on-a-Stick** bem como **NAT (PAT)** para permitir traduzir vários IPs privados para sairem com apenas um IP público pela Internet.

O objetivo principal é mostrar, de forma prática, como diferentes VLANs podem se comunicar de maneira eficiente e segura através de um router.

---

## 🎯 Objetivos
- Criar e configurar múltiplas VLANs em um switch
- Configurar portas em modo **access** e **trunk**
- Implementar o serviço **DHCP** para cada VLAN
- Configurar **Router-on-a-Stick** para roteamento inter-VLAN
- Testar a conectividade entre dispositivos

---

## 🖼️ Topologia da Rede
![Topologia da Rede](docs/topologia.png)

---

## 🗂️ Estrutura do Projeto
