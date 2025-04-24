# Sistema de Monitoramento de Ambiente - Vinheria Agnello

## Descrição do Projeto:

Este é o projeto do desenvolvimento de um sistema de monitoramento para a Vinheria Agnello, que, como solicitado, visa garantir as condições adequadas de luminosidade, temperatura e umidade no ambiente de armazenamento de vinhos. Utilizando o Arduino, o sistema capturará dados em tempo real e fornecerá alertas, tanto visuais como sonoros caso os níveis de qualquer uma das variáveis estejam fora das condições ideais para a preservação da qualidade do vinho.

### Dependências:

Para a implementação deste projeto, você precisará dos seguintes componentes:

- Protoboard (opcional, para montagem).
- Arduino Uno ou um modelo compatível.
- LDR (Resistor Dependente de Luz).
- Resistor (para o LDR).
- Sensor de Temperatura e Umidade.
- 1 Buzzer ativo.
- 3 LEDs (verde, amarelo e vermelho).
- 3 resistores (para os LEDs).
- Fios de conexão.


- Luminosidade: Capturar a luminosidade do ambiente utilizando o LDR.
- Temperatura: Medir a temperatura do ambiente usando o sensor.
- Umidade: Medir a umidade do ar com o mesmo sensor mencionado anteriormente.
- Alarmes: Implementar um sistema de alarme com LEDs e um buzzer para indicar as condições do ambiente:
 - LED Verde: Significa que as condições estão dentro dos limites ideais.
  - LED Amarelo: Condições em alerta.
  - LED Vermelho: Condições fora dos limites!
- Soar uma buzina por 3 segundos quando qualquer uma das variáveis estiver em nível diferente do ideal, repetindo-a enquanto a situação não se normalizar.
