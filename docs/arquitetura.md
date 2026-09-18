# Arquitetura do projeto

[Voltar ao README](../README.md)

A miniestação meteorológica foi desenvolvida em 2025 pelo Clube de Robótica de Potim/SP como uma atividade educacional de aquisição, transmissão e visualização de dados ambientais.

## Visão conceitual

O projeto reuniu Arduino Nano, DHT11, um sensor de pressão atmosférica, ESP8266, conexão Wi-Fi e ThingSpeak. Baterias e um painel solar integraram a proposta de alimentação; a estrutura física utilizou PVC.

```text
DHT11 e sensor de pressão
           ↓
      Arduino Nano
           ↓
        ESP8266
           ↓
          Wi-Fi
           ↓
       ThingSpeak
           ↓
Visualização de dados ambientais
```

Este fluxo descreve a organização conceitual do projeto. Não é um esquema elétrico nem comprova a operação contínua de cada etapa. A distribuição exata das funções entre Arduino e ESP8266 precisa ser conferida no firmware original.

## Partes em desenvolvimento e planejamento

- **Em desenvolvimento:** sensores de velocidade e direção do vento, com impressão 3D e componentes de baixo custo, desenvolvidos pelos alunos. Não foi fornecido registro de conclusão ou integração final.
- **Planejada e não finalizada:** comparação com uma estação meteorológica profissional instalada em uma escola municipal.
- **Interrupção:** a descontinuidade do Clube de Robótica impediu a continuidade das atualizações e a conclusão das etapas pendentes.

## Dados técnicos a recuperar

- [A PREENCHER: modelo do sensor de pressão e variante do ESP8266.]
- [A PREENCHER: firmware original e funções executadas por cada placa.]
- [A PREENCHER: interfaces de comunicação, ligações, alimentação e intervalos de aquisição e envio.]
- [A PREENCHER: registros que permitam identificar o estado de funcionamento de cada etapa na época.]

Veja também o [diagrama de blocos](../hardware/diagrama-blocos.md), o [registro de ligações](../hardware/esquema-ligacoes.md) e a [alimentação solar](alimentacao-solar.md).
