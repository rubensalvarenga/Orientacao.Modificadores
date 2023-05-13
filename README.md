# Orientacao.Modificadores
Public, private, protected
Os modificadores de acesso em C# são palavras-chave que definem o nível de acesso aos membros (métodos, propriedades, campos, etc.) de uma classe.  

Eles controlam quais partes do código podem acessar e manipular esses membros. Existem quatro modificadores de acesso principais em C#: 

 

1. `public`: 

   - Exemplo prático: Imagine uma classe `Pessoa` com uma propriedade `Nome` definida como `public`. Isso significa que o nome pode ser acessado e modificado de qualquer lugar do código. 

   - Explicação: Um membro público é acessível de qualquer lugar, dentro ou fora da classe que o define. Ele oferece a maior visibilidade possível. 

  

2. `private`: 

   - Exemplo prático: Suponha que uma classe `ContaBancaria` tenha um campo `saldo` definido como `private`. Nesse caso, somente os métodos internos da classe podem acessar e modificar o saldo. 

   - Explicação: Um membro privado é acessível apenas dentro da própria classe em que foi declarado. Isso é útil para esconder detalhes de implementação e fornecer encapsulamento. 

  

3. `protected`: 

   - Exemplo prático: Considere uma classe `Animal` com um método `EmitirSom()` definido como `protected`. Isso significa que o método só pode ser acessado por classes derivadas (subclasses) da classe `Animal`. 

   - Explicação: Um membro protegido é acessível dentro da própria classe, bem como em classes derivadas. Isso permite que as classes derivadas herdem e usem o membro protegido. 

  

4. `internal`: 

   - Exemplo prático: Digamos que você tenha um projeto com várias classes, e uma delas possui um método `ProcessarDados()` definido como `internal`. Isso significa que o método só pode ser acessado por classes dentro do mesmo assembly (projeto). 

   - Explicação: Um membro interno é acessível apenas dentro do mesmo assembly. Ele restringe o acesso a classes dentro do mesmo projeto ou assembly. 

  

Além desses modificadores de acesso básicos, existem também os modificadores `protected internal` e `private protected`, que combinam os comportamentos dos modificadores `protected` e `internal` para permitir diferentes níveis de acesso em cenários específicos. 

  

Os modificadores de acesso são importantes para controlar a visibilidade e o acesso a membros em um programa. Eles ajudam a estabelecer o encapsulamento adequado, permitindo que você proteja informações sensíveis e forneça interfaces claras para interagir com uma classe. 
