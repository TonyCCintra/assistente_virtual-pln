# Assistente Virtual com PLN

Este projeto implementa um sistema de assistente virtual utilizando Processamento de Linguagem Natural (PLN).

## Como Funciona

1.  O sistema utiliza a biblioteca `gTTS` para converter texto em fala (Text-to-Speech).
2.  A biblioteca `SpeechRecognition` é usada para tentar converter fala em texto (Speech-to-Text), embora a funcionalidade completa possa ter limitações no ambiente Colab. A entrada de texto pode ser simulada para testar o sistema.
3.  O sistema processa comandos de texto (ou, idealmente, comandos de voz) para realizar ações específicas.
4.  As ações implementadas incluem:
    * Pesquisar informações na Wikipedia.
    * Abrir o YouTube no navegador.
    * Simular a localização de farmácias próximas no Google Maps.

## Como Executar

O código do assistente virtual está no ficheiro `assistente_virtual.ipynb`. Pode abrir e executar este ficheiro no Google Colab.

Para testar o sistema, execute as células no Colab. Pode interagir com o assistente digitando comandos no console, como:

* `wikipedia [termo de pesquisa]` - Para pesquisar algo na Wikipedia.
* `abrir youtube` - Para abrir o YouTube.
* `localizar farmácia` - Para simular a localização de farmácias próximas.
* `sair` ou `encerrar` - Para terminar a execução do assistente.

## Próximos Passos (Opcional)

* Melhorar a funcionalidade de Speech-to-Text para funcionar de forma mais fiável no Colab ou noutros ambientes.
* Adicionar mais funcionalidades e comandos ao assistente.
* Explorar outras bibliotecas de PLN para melhorar a compreensão da linguagem natural.
