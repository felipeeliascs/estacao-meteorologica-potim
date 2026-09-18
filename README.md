# Estação Meteorológica de Potim

Miniestação meteorológica de baixo custo desenvolvida em **2025 no Clube de Robótica do município de Potim/SP**, como uma atividade educacional de construção, programação e Internet das Coisas (IoT).

A atividade envolveu Arduino, sensores ambientais, conectividade Wi-Fi e ThingSpeak para trabalhar a aquisição, a transmissão e a visualização de dados ambientais. Este repositório preserva o contexto do projeto e organiza sua documentação inicial.

> **Situação do projeto:** o desenvolvimento foi interrompido devido à descontinuidade do Clube de Robótica. Os sensores de vento estavam em desenvolvimento e a comparação com uma estação profissional não foi finalizada. Esta documentação distingue o que foi relatado como realizado, o que estava em desenvolvimento e o que ficou planejado.

## O projeto de 2025

A miniestação utilizou:

- **Arduino Nano**;
- **DHT11**, para temperatura e umidade;
- **sensor de pressão atmosférica**, cujo modelo ainda precisa ser documentado;
- **ESP8266**, conectividade **Wi-Fi** e a plataforma **ThingSpeak**;
- **baterias e painel solar**, com especificações e circuito de alimentação ainda a documentar;
- **estrutura em canos de PVC**.

Os alunos também desenvolviam sensores de **velocidade e direção do vento** e seus suportes, com **impressão 3D e componentes de baixo custo**. Essa parte não foi concluída.

Foi planejada uma comparação entre os dados da miniestação de baixo custo e os de uma estação meteorológica profissional instalada em uma escola municipal. A comparação não foi finalizada; este repositório não apresenta resultados comparativos ou validação de precisão.

O projeto foi apresentado e exposto no **INPE Portas Abertas 2025**, em **São José dos Campos/SP**, junto ao então **Projeto Educação**, atualmente **Programa Educação**.


### Alguns registros do projeto

<p align="center">
  <img src="Prot%C3%B3tipo%20v1.png" alt="Protótipo da Estação Meteorológica Educacional de Potim" width="31%">
  <img src="Pr%C3%A1tica%20%281%29.jpg" alt="Atividade prática do Clube de Robótica de Potim" width="31%">
  <img src="INPE%20de%20Portas%20Abertas.jpg" alt="Apresentação da Estação Meteorológica no INPE Portas Abertas 2025" width="31%">
</p>

Mais registros estão organizados no [índice de imagens](imagens/README.md).

## Objetivo educacional

Registrar uma experiência de aprendizagem que reuniu construção de protótipos, programação, sensores, comunicação de dados e conceitos de IoT. O uso de materiais de baixo custo e o desenvolvimento de peças pelos alunos faziam parte dessa experiência.

As informações históricas desta versão foram fornecidas pelo responsável pelo repositório. O repositório já inclui registros fotográficos do protótipo, das atividades com estudantes, dos testes na escola, de dados coletados e da apresentação no INPE Portas Abertas 2025. Também foi incorporado, apenas como referência complementar, um conjunto de modelos 3D de terceiro para estação meteorológica.

## Visão geral

Fluxo conceitual da informação, baseado na descrição do projeto:

```text
DHT11 + sensor de pressão
            |
       Arduino Nano
            |
         ESP8266
            |
          Wi-Fi
            |
        ThingSpeak
            |
   Visualização dos dados
```

As interfaces, ligações e configurações exatas precisam ser confirmadas. A alimentação envolvia painel solar e baterias, mas sua topologia elétrica ainda não está documentada. Os sensores de vento não são apresentados como uma integração concluída.

Veja a [arquitetura](docs/arquitetura.md) e o [diagrama de blocos](hardware/diagrama-blocos.md).

## Organização do repositório

```text
estacao-meteorologica-potim/
├── README.md
├── LICENSE
├── firmware/
│   └── README.md
├── docs/
│   ├── arquitetura.md
│   ├── componentes.md
│   ├── montagem.md
│   ├── alimentacao-solar.md
│   ├── comunicacao-thingspeak.md
│   ├── comparacao-estacao-profissional.md
│   ├── sensores-vento.md
│   ├── contexto-educacional.md
│   └── roadmap.md
├── hardware/
│   ├── diagrama-blocos.md
│   └── esquema-ligacoes.md
├── modelos-3d/
│   └── README.md
├── imagens/
│   └── README.md
└── references/
    └── fontes.md
```

## Documentação

| Documento | Conteúdo |
| --- | --- |
| [Arquitetura](docs/arquitetura.md) | Organização conceitual e lacunas técnicas |
| [Componentes](docs/componentes.md) | Materiais relatados e especificações pendentes |
| [Montagem](docs/montagem.md) | Estrutura física e registros necessários |
| [Alimentação solar](docs/alimentacao-solar.md) | Painel, baterias e dados ainda ausentes |
| [Comunicação com o ThingSpeak](docs/comunicacao-thingspeak.md) | Fluxo de dados e configuração a documentar |
| [Comparação com a estação profissional](docs/comparacao-estacao-profissional.md) | Objetivo planejado e trabalho não finalizado |
| [Sensores de vento](docs/sensores-vento.md) | Desenvolvimento interrompido |
| [Contexto educacional](docs/contexto-educacional.md) | Clube de Robótica e exposição no INPE |
| [Roadmap](docs/roadmap.md) | Pendências e possibilidades de continuidade |
| [Esquema de ligações](hardware/esquema-ligacoes.md) | Modelo de registro, ainda sem pinagem confirmada |

## Como completar este registro

Os marcadores **[A PREENCHER: ...]** identificam informações ainda ausentes. Devem ser substituídos apenas por dados confirmados em registros ou no protótipo. A lista de pendências está no [roadmap](docs/roadmap.md).

O diretório [firmware](firmware/README.md) está reservado para o código efetivamente utilizado. Ainda não há firmware disponível para compilar ou instruções completas para reproduzir a montagem.

## Registros visuais do projeto

O repositório inclui fotografias e imagens produzidas durante o desenvolvimento e a divulgação do projeto. Entre os registros disponíveis estão:

- [Protótipo v1](Prot%C3%B3tipo%20v1.png);
- [Estação v1](Esta%C3%A7%C3%A3o%20v1.png);
- [Anemômetro — registro 1](Anem%C3%B4metro%20%281%29.jpg);
- [Anemômetro — registro 2](Anem%C3%B4metro%20%282%29.jpg);
- [Direção do vento](Dire%C3%A7%C3%A3o%20do%20Vento.jpg);
- [Prática com estudantes — registro 1](Pr%C3%A1tica%20%281%29.jpg);
- [Prática com estudantes — registro 2](Pr%C3%A1tica%20%282%29.jpg);
- [Prática com estudantes — registro 3](Pr%C3%A1tica%20%283%29.jpg);
- [Teste na escola — registro 1](Teste%20na%20escola%201.jpg);
- [Teste na escola — registro 2](Teste%20na%20escola%202.png);
- [Vídeo de teste na escola](Teste%20na%20escola%203.mp4);
- [Dados coletados](Dados%20Coletados.png);
- [Resultados](Resultados.jpg);
- [Apresentação do projeto no Programa Educação](Apresenta%C3%A7%C3%A3o%20do%20Projeto%20no%20Programa%20Educa%C3%A7%C3%A3o.png);
- [INPE Portas Abertas 2025](INPE%20de%20Portas%20Abertas.jpg).

Esses arquivos documentam o processo de desenvolvimento e divulgação do projeto. Eles não devem ser interpretados como comprovação de validação metrológica da miniestação.

## Modelos 3D externos — referência complementar

Foi adicionado ao repositório o conjunto **LTB Weather Station**, criado pelo usuário **RobWLakes** e publicado no Thingiverse:

- Fonte original: https://www.thingiverse.com/thing:2849562
- Pasta preservada no repositório: [LTB_Weather_Station_2849562](LTB_Weather_Station_2849562/)
- Arquivos STL e fontes OpenSCAD: [files/](LTB_Weather_Station_2849562/files/)

Esse conjunto **não foi desenvolvido pelos alunos do Clube de Robótica de Potim** e não deve ser confundido com as peças que estavam sendo criadas no projeto. Ele foi incluído como **referência externa de modelagem e possibilidade de continuidade**, especialmente para anemômetro, direção do vento, pluviômetro e estrutura.

O arquivo de licença fornecido pelo projeto original informa licença **cc-nc**. Portanto, esses arquivos de terceiro **não estão cobertos pela licença MIT deste repositório** e devem ser utilizados conforme os termos definidos pelo autor original.

Veja também a documentação em [modelos-3d/README.md](modelos-3d/README.md).

## Referência técnica e atribuição

O artigo **[Estação meteorológica com Arduino](https://embarcados.com.br/estacao-meteorologica-com-arduino/)**, de **Igor Fonseca Albuquerque**, publicado no **Embarcados em 25 de maio de 2016**, foi utilizado como referência técnica.

O projeto de Potim foi uma **adaptação educacional**, com escolhas de componentes e desenvolvimento próprios do contexto do Clube de Robótica, **não uma cópia integral** do projeto descrito no artigo. As especificações da referência não devem ser tomadas como especificações confirmadas da miniestação de Potim. Esta versão não reproduz o código nem as imagens do artigo.

Consulte os [registros de fontes e materiais pendentes](references/fontes.md).

## Licença

O conteúdo original do projeto de Potim publicado neste repositório está sob a [licença MIT](LICENSE), quando aplicável.

Materiais externos preservam suas próprias licenças. Em particular, os arquivos do diretório [LTB_Weather_Station_2849562](LTB_Weather_Station_2849562/) são de autoria de **RobWLakes**, foram obtidos a partir do Thingiverse e possuem licença própria indicada no arquivo [LICENSE.txt](LTB_Weather_Station_2849562/LICENSE.txt). Esses arquivos não estão cobertos pela licença MIT do restante do repositório.
