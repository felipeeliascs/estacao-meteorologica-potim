# Diagrama de blocos

Este diagrama representa o fluxo conceitual relatado para o projeto. As setas indicam a circulação da informação, sem especificar pinos, protocolos ou circuitos elétricos.

```text
    DHT11          Sensor de pressão
      |                   |
      +---------+---------+
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

## Alimentação e estrutura

- Alimentação relatada: painel solar e baterias.
- Estrutura física relatada: canos de PVC.
- [A PREENCHER: topologia de alimentação, interligações, tensões e eventuais circuitos de carga, proteção ou regulação efetivamente utilizados].
- [A PREENCHER: dimensões, disposição dos elementos e fixações na estrutura].

Não é possível representar um circuito de alimentação reproduzível com os dados disponíveis. Veja [alimentação solar](../docs/alimentacao-solar.md).

## Parte em desenvolvimento

Os sensores de velocidade e direção do vento e seus suportes estavam sendo desenvolvidos pelos alunos com impressão 3D e componentes de baixo custo. Não integram este diagrama como sensores concluídos ou conectados.

[A PREENCHER: desenho e forma de integração previstos para os sensores de vento, se houver registros].

Veja a [arquitetura](../docs/arquitetura.md), o [esquema de ligações](esquema-ligacoes.md) e os [sensores de vento](../docs/sensores-vento.md).
