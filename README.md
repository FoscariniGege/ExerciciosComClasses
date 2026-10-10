Módulo: Introdução a Classes e Orientação a Objetos (POO) em Java
Este repositório documenta a consolidação da minha base em Programação Orientada a Objetos (POO) com Java. Esta pasta centraliza os primeiros 5 exercícios práticos do curso, representando a transição crucial da programação procedural (com tudo concentrado no método main) para uma arquitetura limpa, modular e orientada a objetos, aplicando os princípios de Clean Code.

🚀 O que foi estudado e aplicado em todo o módulo
Separação de Pacotes (entities e application): Isolamento claro entre as regras de negócio das entidades e a execução principal do sistema.

Atributos e Métodos de Instância: Compreensão de como criar moldes próprios e permitir que os objetos manipulem os seus próprios dados.

Encapsulamento de Comportamentos: Delegação de regras matemáticas e lógicas complexas para dentro das próprias classes.

Mutabilidade de Estado: Capacidade de atualizar valores internos de um objeto em tempo real por meio de métodos específicos.

Lógica Condicional Encapsulada: Tomada de decisões e formatações dinâmicas utilizando estruturas if/else dentro do objeto.

Uso do método toString(): Sobrescrita para permitir que os objetos gerem sua própria representação textual formatada, mantendo o programa principal limpo.

💻 Os 5 Exercícios Resolvidos nesta Pasta
Calculadora de Área de Triângulos (Com e Sem Classes):

Evolução Inicial: Comparação prática da mesma lógica implementada primeiro de forma procedural (variáveis soltas no main) e, em seguida, migrada para uma classe dedicada Triangle aplicando a Fórmula de Heron.

Controle de Estoque de Produtos (Product):

Foco: Gerenciamento de estado e fluxo de mercadorias. O sistema calcula o valor total investido no estoque e permite realizar entradas (AddProducts) e saídas (RemoveProducts), exibindo o estado atualizado com o toString().

Cálculo de Medidas do Retângulo (Retangulo):

Foco: Encapsulamento de fórmulas geométricas. A classe calcula de forma independente a Área, o Perímetro e a Diagonal (utilizando o Teorema de Pitágoras com Math.sqrt).

Gestão de Funcionários (Funcionario):

Foco: Mutabilidade e regras financeiras. O sistema calcula o salário líquido (descontando o imposto) e aplica aumentos percentuais que afetam estritamente o salário bruto do colaborador.

Sistema de Avaliação de Alunos (Aluno):

Foco: Lógica condicional e formatação dinâmica. A classe soma as notas dos trimestres, avalia se o estudante atingiu a média mínima de aprovação (PASS / FAILED) e calcula automaticamente quantos pontos faltam em caso de reprovação.

🛠️ Tecnologias e Ferramentas Utilizadas
Linguagem: Java

Entrada e Saída: Scanner e String.format (com formatação avançada de casas decimais e quebras de linha %n)

Bibliotecas Nativas: Math.sqrt para cálculos de raiz quadrada

Conceitos de POO: Classes, instâncias, encapsulamento, métodos com e sem retorno, mutabilidade e sobrescrita do toString().
