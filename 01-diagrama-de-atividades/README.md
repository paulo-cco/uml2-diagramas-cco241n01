# Diagrama de Atividades

**Grupo 1:** Paulo, Davi e Isaac

## Definição

O Diagrama de Atividades é um diagrama comportamental da UML utilizado para representar o fluxo de execução de um processo ou sistema. Ele demonstra a sequência de ações, decisões, caminhos alternativos e atividades que podem acontecer simultaneamente.

Seu principal objetivo é facilitar a compreensão da lógica de um processo, mostrando visualmente como ele começa, se desenvolve e termina.

## Quando usar

É utilizado durante a análise e modelagem de sistemas, principalmente quando precisamos representar processos de negócio, fluxos de trabalho, regras de decisão e atividades paralelas.

É especialmente útil para detalhar o funcionamento de um processo desde o início até sua conclusão.

## Elementos da notação

| **Símbolo** | **Nome** | **O que representa** |
|---|---|---|
| Círculo preenchido | Nó inicial | Indica onde o fluxo começa. |
| Retângulo com bordas arredondadas | Ação/Atividade | Representa uma tarefa executada no processo. |
| Losango | Nó de decisão | Representa uma condição que determina caminhos diferentes. |
| Seta | Fluxo de controle | Indica a sequência de execução das atividades. |
| Círculo com contorno e preenchimento interno | Nó final | Indica o encerramento do processo. |
| Barra horizontal ou vertical | Fork/Join | Representa a divisão e sincronização de atividades paralelas. |

## Exemplo prático

O exemplo prático apresentado pelo grupo utiliza um processo de pedido de e-commerce. O diagrama demonstra etapas como a realização do checkout, a validação do pagamento, a separação dos produtos e o despacho do pedido.

O objetivo é mostrar a sequência das atividades, as decisões envolvidas e como o processo ocorre até a conclusão do pedido.

[Exemplo prático do grupo](./Diagrama%20de%20Atividades.png)

## Comparação com Caso de Uso, Classe e Sequência

Todos são diagramas da UML utilizados para representar diferentes aspectos de um sistema, mas possuem finalidades distintas:

- **Diagrama de Caso de Uso:** apresenta as funcionalidades do sistema e a interação dos usuários com ele.
- **Diagrama de Classes:** representa a estrutura do sistema, mostrando classes, atributos, métodos e relacionamentos.
- **Diagrama de Sequência:** demonstra a comunicação entre objetos e a ordem das mensagens ao longo do tempo.
- **Diagrama de Atividades:** representa o fluxo de execução de processos, incluindo ações, decisões e atividades paralelas.

A principal diferença é que o Diagrama de Atividades enfatiza o fluxo de trabalho, enquanto os demais representam funcionalidades, estrutura ou comunicação entre objetos.

## Apresentação

[Apresentação em PDF](./Diagrama%20de%20Atividades%20UML.pdf)

## Referências

- OMG. Unified Modeling Language (UML). https://www.omg.org/spec/UML/
- IBM. Documentação sobre modelagem UML. https://www.ibm.com/docs/
