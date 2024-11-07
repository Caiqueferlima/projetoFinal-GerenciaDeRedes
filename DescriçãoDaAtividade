# Projeto de Configuração de uma Rede Empresarial

## Objetivo
O projeto consiste em projetar e configurar uma rede corporativa simulada, utilizando o Cisco Packet Tracer ou uma ferramenta semelhante. O objetivo é aplicar conceitos como IP, sub-redes, servidores, VLANs, roteamento e explorar novos conceitos através de pesquisa. A rede deve permitir comunicação entre diferentes departamentos e configurar serviços de rede (Web, DHCP e DNS) com segregação via VLANs.

---

## Pesquisa Complementar
Para realizar o projeto, será necessário pesquisa adicional sobre alguns conceitos ainda não abordados em aula. Cada equipe deve buscar informações sobre:

- **Configurações de DHCP, DNS e Web**
- **Roteamento Dinâmico** (OSPF, RIP, etc.)
- **Listas de Controle de Acesso (ACLs)** para segurança de rede

---

## 1. Instruções
### Topologia da Rede
- A rede deve simular uma empresa com pelo menos **3 departamentos** (por exemplo, TI, RH e Administração):
  - **Departamento 1:** Suporte para 30 hosts
  - **Departamento 2:** Suporte para 75 hosts
  - **Departamento 3:** Suporte para 5 hosts
- Cada departamento deve ser configurado com uma **VLAN específica**
- Implementar **roteamento inter-VLAN** entre os departamentos

### Endereçamento IP e Sub-redes
- Definir um **plano de endereçamento IP** utilizando sub-redes para segmentar os departamentos conforme o número de hosts necessário
- Calcular os **intervalos de IP** para cada departamento com base nos requisitos de host

### Servidores e Serviços
- Configurar um **servidor DHCP** para fornecer IPs automaticamente para cada VLAN/departamento
- Implementar um **servidor DNS** para resolver domínios locais, como `adm.s3sistemas.local` e `intranet.s3sistemas.local`
- Configurar um **servidor Web** acessível internamente para hospedar o site da empresa (exibir informações da equipe na página HTML)

### Roteamento
- Implementar **roteamento estático ou dinâmico** (ex.: OSPF ou RIP) entre as sub-redes para permitir a comunicação entre departamentos

### Segurança e Acesso
- Configurar **ACLs** no roteador para controlar o tráfego entre VLANs
- Implementar regras que limitem o acesso a determinados serviços, como restringir o domínio `adm.s3sistemas.local` apenas para hosts do setor de Administração

---

## 2. Documentação do Projeto e Apresentação
### Planejamento da Rede
- Definir o **esquema de endereçamento IP** e a topologia da rede
- Especificar o **equipamento utilizado** (modelos de switches e roteadores)
- Dividir a rede em sub-redes, calculando IPs de acordo com o número de hosts necessários
- Documentar cada sub-rede, incluindo IP de rede, intervalo de IPs válidos, broadcast e máscara no formato padrão

### Configuração dos Equipamentos de Rede
- Configurar os **switches** para suportar VLANs
- Configurar o **roteador** para roteamento inter-VLAN e, se possível, conceder acesso à Internet
- Configurar os **servidores DHCP, DNS e Web** para atender à demanda da rede

### Testes
- Testar a **conectividade entre VLANs** e a comunicação entre servidores
- Verificar se o **DHCP** está distribuindo IPs corretamente
- Testar a **resolução de nomes** via DNS e o acesso ao servidor Web

### Resumo
- Documentar o processo completo, incluindo topologia, endereçamento IP, configurações de roteamento e servidores
- Apresentar o projeto, explicando as decisões de design e os resultados (caso o grupo não consiga realizar alguma configuração, documentar os erros encontrados)

---
