# HSF – Endoscopia | Dashboard de Sobreaviso — v4

## Regra temporal dos plantões

A data da escala é a **data de origem do plantão**.

### Plantão de 24h
- início: 07:00 da data de origem
- término: 06:59 do dia seguinte

Exemplo: o plantão de 05/09 pertence integralmente a 05/09, embora termine em 06/09 às 06:59.

### Plantão de 12h
- início: 19:00 da data de origem
- término: 06:59 do dia seguinte

### Comportamento do dashboard
Entre 00:00 e 06:59, o dashboard continua exibindo o plantão iniciado no dia anterior.
Em dias de plantão de 12h, entre 07:00 e 18:59, o médico do dia aparece como próximo plantonista e o status informa que o plantão inicia às 19:00.

## Contagem mensal
A contagem é sempre pela data de origem:
- plantão iniciado no último dia do mês e terminado no mês seguinte conta integralmente no mês de origem.

## Escala completa
A tabela mostra:
- data de origem
- dia da semana
- médico
- duração
- início
- término
- motivo

## Versão
Rodapé: **v4**
