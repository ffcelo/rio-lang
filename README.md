# rio-lang

Autor: Marcelo de França

Rio é uma linguagem de programação orientada a objetos que simplifica o Java para a criação de jogos e pequenos aplicativos, fácil de usar e aprender.

Objetivos da linguagem:
- sintaxe clara, preferindo palavras-chave a símbolos
- inferência de tipos
- getters e setters simplificados
- criação rápida de classes, numa única linha de código
- métodos inicializadores inteligentes
- poucas estruturas (apenas um único jeito de fazer cada coisa)
- açúcares sintáticos variados

Versão 1: implementação do compilador básico, com os seguintes itens:
- objeto (sem herança, genéricos e inicializadores)
- método (apenas retornando expressão simples)
- atributo (sem literais, apenas tipo)

Exemplo:
   class Alfa
      var alfa: Int
      def alfa() = alfa
