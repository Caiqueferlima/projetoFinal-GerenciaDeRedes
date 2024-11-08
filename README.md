# Projeto de Configuração de uma Rede Empresarial

O seguinte projeto faz parte da avaliação final da disciplina de GERE (Gerência de Redes)

## Índice
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Desenvolvimento](#desenvolvimento)
- [Arquitetura do projeto no Cisco Packet Tracer](#arquitetura-do-projeto-no-cisco-packet-tracer)
- [Dificuldades encontradas](#dificuldades-encontradas)
- [Equipe](#equipe)

---

## Tecnologias utilizadas
- Cisco Packet Tracer
- Git para versionamento

## Divisão de Tarefas
A equipe organizou as atividades de maneira dinâmica, dividindo as tasks de acordo com a especialidade e interesse de cada integrante. As decisões sobre a alocação das tasks foram tomadas em conjunto, mantendo uma comunicação constante para apoiar qualquer dificuldade em cada etapa.

A contribuição de cada integrante pode ser observada nos commits do repositório. Vale ressaltar que, embora as tasks tenham sido divididas para fins de organização, todos participaram de cada fase do projeto, pois cada task dependia da subsequente.

## Arquitetura do projeto no Cisco Packet Tracer


## Desenvolvimento
### Planejamento da Rede
- Definir o esquema de endereçamento IP e a topologia da rede
A topologia usada foi o barramento

- Especificar o equipamento utilizado (modelos de switches e roteadores)
3 Roteadores 1941
4 switches 2960-24TT

- Dividir a rede em sub-redes, calculando IPs de acordo com o número de hosts necessários
- Documentar cada sub-rede, incluindo IP de rede, intervalo de IPs válidos, broadcast e máscara no formato padrão
![Projeto no Cisco](./assets/topologia2.png) 

### Configuração dos Equipamentos de Rede
- Configurar os switches para suportar VLANs

Foi criada uma VLAN para cada switch de cada subrede. O de TI, por exemplo, ficou com a VLAN 10 como mostra a imagem abaixo, e os de RH e ADM ficaram com VLAN 20 e 30.
![vlan](./assets/vlan.png) 

- Configurar o roteador para roteamento inter-VLAN e, se possível, conceder acesso à Internet


- Configurar os servidores DHCP, DNS e Web para atender à demanda da rede

### Testes
- Testar a conectividade entre VLANs e a comunicação entre servidores
- Verificar se o DHCP está distribuindo IPs corretamente
- Testar a resolução de nomes via DNS e o acesso ao servidor Web


## Dificuldades encontradas

- Aproveitamento baixo matéria RDC1, dificultando o entendimento geral da matéria;
- Carga Horária reduzida devido a greve e excesso de sábados letivos, dificultando as práticas no software usado;
- Dificuldade na configuração dos roteadores e problemas ao conectar com os switches.


## Equipe
<table align="center">
  <tr align="center">
  <td>
      <a href="https://github.com/Caiqueferlima">
        <img src="https://avatars.githubusercontent.com/u/130234796?v=4" width=100 />
        <p>Caíque <br/>Fernandes</p>
      </a>
    </td>
    <td>
      <a href="https://github.com/emillyjullyane">
        <img src="https://avatars.githubusercontent.com/emillyjullyane" width=100 />
        <p>Emilly <br/>Jullyane</p>
      </a>
    </td>
    <td>
      <a href="https://github.com/Guilhermeleandro-N">
        <img src="https://avatars.githubusercontent.com/Guilhermeleandro-N" width=100 />
        <p>Guilherme <br/>Leandro</p>
      </a>
    <td>
      <a href="https://github.com/mcclara18">
        <img src="https://avatars.githubusercontent.com/mcclara18" width=100 />
        <p>Maria <br/>Clara</p>
      </a>
    </td>
    <td>
      <a href="https://github.com/Rachelee18">
        <img src="https://avatars.githubusercontent.com/Rachelee18" width=100 />
        <p>Raquel <br/>Medeiros</p>
      </a>
  </tr>
