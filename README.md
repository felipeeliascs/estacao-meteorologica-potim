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

## Objetivo educacional

Registrar uma experiência de aprendizagem que reuniu construção de protótipos, programação, sensores, comunicação de dados e conceitos de IoT. O uso de materiais de baixo custo e o desenvolvimento de peças pelos alunos faziam parte dessa experiência.

As informações históricas desta versão foram fornecidas pelo responsável pelo repositório. Código, fotografias, modelos 3D, esquemas completos e conjuntos de dados ainda não foram fornecidos para inclusão.

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

Os marcadores **[A PREENCHER: ...]** identificam informações ausentes. Devem ser substituídos apenas por dados confirmados em registros ou no protótipo. A lista de pendências está no [roadmap](docs/roadmap.md).

O diretório [firmware](firmware/README.md) está reservado para o código efetivamente utilizado. Ainda não há firmware disponível para compilar ou instruções completas para reproduzir a montagem. Os diretórios de [modelos 3D](modelos-3d/README.md) e [imagens](imagens/README.md) também contêm orientações para incorporar os materiais originais.

## Referência técnica e atribuição

O artigo **[Estação meteorológica com Arduino](https://embarcados.com.br/estacao-meteorologica-com-arduino/)**, de **Igor Fonseca Albuquerque**, publicado no **Embarcados em 25 de maio de 2016**, foi utilizado como referência técnica.

O projeto de Potim foi uma **adaptação educacional**, com escolhas de componentes e desenvolvimento próprios do contexto do Clube de Robótica, **não uma cópia integral** do projeto descrito no artigo. As especificações da referência não devem ser tomadas como especificações confirmadas da miniestação de Potim. Esta versão não reproduz o código nem as imagens do artigo.

Consulte os [registros de fontes e materiais pendentes](references/fontes.md).

## Licença

O conteúdo original publicado neste repositório está sob a [licença MIT](LICENSE). A referência técnica externa conserva seus próprios direitos; sua citação não a inclui na licença deste repositório.
