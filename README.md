# PROJETO DE CONFIGURAÇÃO DE UMA REDE EMPRESARIAL

Objetivo:
Os alunos deverão projetar e configurar uma rede corporativa simulada, utilizando o Cisco Packet
Tracer ou uma ferramenta semelhante, aplicando os conceitos aprendidos em aula (IP, sub-redes,
servidores, VLANs, roteamento) e também desbravar novos conceitos através de uma pesquisa na
web. O projeto deve permitir a comunicação entre diferentes departamentos, com serviços de rede
(Web, DHCP e DNS) adequadamente configurados e segregação de redes via VLANs.

## Pesquisa Complementar:
Para realizar este projeto será necessário uma pesquisa envolvendo alguns conceitos que ainda não
foram explorados em sala de aula, desse modo cada equipe deve buscar mais informações sobre:
● Configurações de DHCP, DNS e WEB.
● Roteamento dinâmico (OSPF, RIP, etc.).
● Implementação de ACLs (Listas de controle de acesso) para segurança de rede.

## 1. INSTRUÇÕES:
### Topologia da Rede:
● A rede deve simular uma empresa com pelo menos 3 departamentos (por exemplo, TI, RH e
Administração).
○ Departamento 1: Deve suportar um número de 30 hosts.
○ Departamento 2: Deve suportar um número de 75 hosts.
○ Departamento 3: Deve suportar um número de 5 hosts.
● Cada departamento deve ser configurado com uma VLAN específica.
● O roteamento entre VLANs deverá ser implementado utilizando roteamento inter-VLAN.

### Endereçamento IP e Sub-redes:
● Definir um plano de endereçamento IP para a rede, utilizando sub-redes para segmentar os
diferentes departamentos com o número de hosts indicados.
● Calcular os intervalos de IP apropriados para cada departamento (VLAN) com base no
número de hosts necessários.

### Servidores e Serviços:
● Configurar um servidor DHCP para fornecer endereços IP automaticamente para cada
VLAN/departamento.
● Implementar um servidor DNS que resolva nomes de domínio locais da rede, como
"adm.s3sistemas.local" e “intranet.s3sistemas.local”.
● Configurar um servidor web acessível internamente para hospedar o site da empresa
(configure a página html para exibir as informações da equipe).

### Roteamento:
● Implementar o roteamento estático ou roteamento dinâmico (ex.: OSPF ou RIP) entre as
sub-redes, garantindo que todos os departamentos possam se comunicar.
Segurança e Acesso:
● Configurar listagens de controle de acesso (ACLs) no roteador para controlar o tráfego entre
as VLANs.
● Implementar regras que restrinjam o acesso a certos serviços ou servidores, como por
exemplo: o dominio “adm.s3sistemas.local” só pode ser acessado pelos hosts do setor de
administração.

## 2. DOCUMENTAÇÃO DO PROJETO E APRESENTAÇÃO:
### Planejamento da Rede:
● Definir o esquema de endereçamento IP e topologia da rede.
● Definir equipamento a ser utilizado (modelos de switches e roteadores utilizados)
● Dividir a rede em sub-redes, calculando os endereços IP de acordo com o número de hosts.
● Documentar cada uma das sub-redes, fornecendo informações como: ip de rede, intervalo de
ips válidos, broadcast e máscara (no formato padrão).
### Configuração dos Equipamentos de Rede:
● Configurar os switches para suportar VLANs.
● Configurar o roteador para o roteamento inter-VLAN (e se possível, conceder acesso à
internet).
● Configurar os servidores (DHCP, DNS e Web) para atender as demandas da rede.
Testes:
● Testar a conectividade entre as VLANs e a comunicação entre os servidores.
● Verificar se o DHCP está distribuindo IPs corretamente.
● Testar a resolução de nomes via DNS e o acesso ao servidor web.
### Resumo:
● Documentar todo o processo, incluindo topologia da rede, endereçamento IP, configurações
de roteamento e servidores.
● Cada grupo deverá apresentar seu projeto, explicando as decisões de design e os resultados
obtidos (caso o grupo não consiga realizar determinada configuração, devem documentar os
erros encontrados no processo de configuração da infraestrutura).
