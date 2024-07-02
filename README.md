# Desafio01---DIO---Trilha-Java-B-sico
Desafio - DIO - Trilha Java Básico - Controle de Fluxo 

# Explicação 
Explicações importantes:
ParametrosInvalidosException: É uma classe simples que estende Exception para criar uma exceção personalizada com uma mensagem específica.

Contador (classe principal):

Usa Scanner para ler os parâmetros do terminal (parametroUm e parametroDois).
Chama o método contar(parametroUm, parametroDois) dentro de um bloco try-catch para capturar a exceção ParametrosInvalidosException caso seja lançada.
No método contar(parametroUm, parametroDois), valida se parametroUm é maior ou igual a parametroDois. Se sim, lança a exceção. Caso contrário, executa um loop for para imprimir os números de parametroUm + 1 até parametroDois.
Esse código atende aos requisitos especificados, lidando adequadamente com entrada de dados, validação e exceções personalizadas.

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
