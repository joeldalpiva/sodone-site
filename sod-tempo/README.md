# SOD Tempo Inteligente — Base de Execução

Módulo isolado para Tempario, sugestão automática de mão de obra, POP executável e aprendizado pelo tempo real da oficina.

## Montadoras — lote inicial
Volkswagen, Chevrolet, Fiat, Ford, Toyota, Renault, Jeep, Honda, Hyundai e Nissan.

## Fluxo
1. A OS identifica montadora, modelo, motor e ano.
2. Ao digitar um serviço, o SOD pesquisa aplicações compatíveis.
3. Sugere Tempo SOD e valor de mão de obra conforme valor/hora da categoria.
4. Mantém Tempo Montadora/Referência separado e imutável.
5. Após aprovação, o serviço vira uma Missão de Execução.
6. O técnico segue POP passo a passo, registrando evidências, medições, torques e pausas.
7. O cronômetro registra tempo produtivo real.
8. O controle final encerra a missão e alimenta o histórico daquele serviço/veículo.
9. Indicadores gerenciais ficam ocultos do técnico.

## Fontes e confiança
- Montadora/Oficial
- Base técnica confirmada
- Histórico Dalpiva
- Pendente/estimado

Nunca apresentar estimativa como dado oficial.

## Modelo do serviço
Cada aplicação deve conter: montadora, modelo, motor, faixa de ano, categoria, serviço, tempo de referência, fonte, Tempo SOD, valor/hora da categoria, POP, etapas, ferramentas, torques/especificações, pontos de atenção, evidências obrigatórias, critérios de aprovação, lições aprendidas, tempo produtivo médio, número de execuções e status de confiança.

## Execução perfeita
A avaliação interna combina conformidade do POP, registros/evidências obrigatórios, tempo de execução, controle final e ausência de retorno/garantia. A pontuação individual é gerencial e não aparece na tela do técnico.
