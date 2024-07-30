# Trabalho 2 - Redes de Computadores I - Algoritmo Árvore B+

## Pré-requisitos

Antes de executar o código, certifique-se de que você tenha os seguintes pacotes Python instalados:
- networkx
- matplotlib
- tkinter

Você pode instalar esses pacotes utilizando o seguinte comando:

```
pip install networkx matplotlib
```

## Estrutura do Código

O código está estruturado da seguinte maneira:

1. Importação de Bibliotecas: As bibliotecas necessárias (networkx, matplotlib, random e tkinter) são importadas.
2. Definição de Funções:
    - `gerar_custo()`: Gera um custo aleatório para as conexões entre roteadores.
    - `melhor_caminho_bplus(G, inicio, fim)`: Encontra o melhor caminho entre dois roteadores utilizando uma abordagem de árvore B+.
    - `visualizar_rede(G, caminho=None, resumo=None)`: Visualiza a rede de roteadores e destaca o melhor caminho encontrado.
    - `obter_entrada()`: Interface gráfica para obter a entrada do usuário (roteadores de início e fim).
3. Criação da Rede de Roteadores:
    - Os roteadores são adicionados à rede com rótulos formatados.
    - As conexões entre os roteadores são adicionadas com custos aleatórios.
4. Execução do Código:
    - A função `obter_entrada()` é chamada para obter os roteadores de início e fim.
    - A função `melhor_caminho_bplus(G, inicio, fim)` encontra o melhor caminho entre os roteadores especificados.
    - A função `visualizar_rede(G, caminho, resumo)` visualiza a rede com o caminho encontrado destacado.

## Passos para Executar o Código

1. Execute o Arquivo Python:
    - Abra o terminal (ou prompt de comando) e navegue até o diretório onde o arquivo `arvoreB.py` está salvo.
    - Execute o arquivo utilizando o seguinte comando:
      ```
      python arvoreB.py
      ```

2. Interaja com a Interface Gráfica:
    - Uma janela gráfica aparecerá pedindo para você digitar o número do roteador de início e fim.
    - Digite os números conforme solicitado e clique em "OK".
    - Após inserir os números, o código encontrará o melhor caminho entre os roteadores especificados e exibirá o resultado no terminal.
    - Uma visualização gráfica da rede será exibida em uma janela do matplotlib, destacando o melhor caminho encontrado.

## Observações

- Certifique-se de que os números dos roteadores de início e fim inseridos estão dentro do intervalo permitido (0 ou 2 até 5 ou 7 até 11).
- A visualização da rede é gerada utilizando matplotlib, então a janela da visualização pode demorar alguns segundos para aparecer, dependendo do desempenho do seu sistema.
