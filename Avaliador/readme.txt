AVALIADOR

O arquivo Avaliador.java é uma classe Java (servindo de API quando instanciada) que:

Avalia uma expressão matemática (em String) com ou sem variáveis previamente definidas pelo usuário.

MODELO DE NÚMERO:

O modelo de número é tradicional: +(ou)-123.456E+(ou)-789

Obs.: '+' e '-' e a notação científica são opcionais, 'E' sempre maiúsculo.

VARIÁVEIS:

As variáveis recebem como nome uma String e como valor um número (double) ou uma expressão matemática (String), a qual pode até citar outras variáveis.

Cuidado, pois pode haver loop se os valores das variáveis ficarem referenciando outras variáveis indefinidamente.

OPERADORES:

^ (Exponenciação), * , / , % (Módulo), + , -

TRATAMENTO DE ERROS:

Se o usuário cometer erros de sintaxe, esta classe lança erros com mensagens personalizadas.

---

Segue junto também uma pasta com javadoc.

@author Lucas Paz.
