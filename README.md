# threads em python

## Descrição
Este script em Python demonstra o uso de threads para simular a corrida de dois carros com velocidades diferentes. O módulo `threading` é utilizado para criar threads separadas para cada carro, permitindo que eles avancem simultaneamente em um percurso fictício.

## Funcionalidades
- Duas threads são criadas, representando dois carros com velocidades diferentes.
- Cada carro avança em um trajeto fictício, imprimindo informações sobre o piloto e a distância percorrida.
- A função `carro` é utilizada para simular o movimento de um carro.

## Requisitos
Certifique-se de ter o Python instalado em seu ambiente para executar o script.

## Como Executar
1. Abra um terminal no diretório onde o arquivo `threads.py` está localizado.
2. Execute o comando:

    ```bash
    python threads.py
    ```

## Resultado Esperado
Os dois carros iniciarão a corrida simultaneamente. O carro do piloto 'Bruno' avançará a uma velocidade de 1 unidade a cada 0.5 segundos, enquanto o carro do piloto 'Python' avançará a uma velocidade de 1.5 unidades a cada 0.5 segundos.

Exemplo de saída:
```
Piloto: Bruno Km: 1
Piloto: Python Km: 1.5
Piloto: Bruno Km: 2
Piloto: Python Km: 3
...
```

## Observações
- Este script é um exemplo simples e educativo para ilustrar o conceito de threads em Python.
- Ajuste as velocidades, tempos de sono e outras variáveis conforme necessário para experimentar diferentes cenários.

**Nota:** Certifique-se de compreender as implicações do uso de threads, como potenciais condições de corrida, ao aplicar esse conceito em projetos mais complexos.
