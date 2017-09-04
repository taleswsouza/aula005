# Aula 005

## Prática

### Herança: Classe **Object** com *Camisa* / *UsaCamisa*

1. Criar um novo projeto chamado **Heranca** (SEM classe principal)
2. Criar um novo pacote chamado **com.aula.heranca.camisa**
4. Criar uma nova _Classe Java_ chamada **Camisa**
* (pag.120) Exemplo 7.11 – Listagem da classe Camisa
```java
package com.aula.heranca.camisa;
public class Camisa {
    public String marca;
    public int numero;
    public double preco;
}
```
3. Criar uma nova _Classe Principal Java_ chamada **UsaCamisa** (está classe irá conter o método main)
* (pag.121) Exemplo 7.12 – Listagem da classe UsaCamisa
```java
package com.aula.heranca.camisa;
public class UsaCamisa {
    public static void main(String[] args) {
        Camisa camisa = new Camisa();
        System.out.println(camisa.getClass());
        System.out.println(camisa.getClass().getSimpleName());
        System.out.println(camisa.hashCode());
    }
}
```

Repare que os métodos *getClass() / getClass().getSimpleName() / hashCode()* não existem na classe **Camisa**

Fique atento que tanto estas quanto às demais classes serão criadas em pacotes diferentes dos exemplos do livro (**com.aula.heranca.camisa** ao invés de **cap07**)

### Herança: Usando **```extends```** com **Pessoa** / **PessoaFisica** / **PessoaJuridica**

Seguindo o diagrama UML apresentado na pag.123 **Figura 7.8 – Diagrama de classes de acordo com a UML** construa as classes abaixo:

1. Dentro do projeto Heranca, crie um novo pacote chamado **com.aula.heranca.pessoa**
* Fique atento as classes abaixo serão criadas no pacote **com.aula.heranca.pessoa** (ao invés de *cap07*)
2. Criar uma nova _Classe Java_ chamada **Pessoa**
* Siga o exemplo da ```pag.121``` - Exemplo 7.13 – A classe Pessoa
3. Criar uma nova _Classe Java_ chamada **PessoaFisica**
* Siga o exemplo da ```pag.122``` - Exemplo 7.14 – A classe PessoaFisica
4. Criar uma nova _Classe Java_ chamada **PessoaJuridica**
* Siga o exemplo da ```pag.122``` - Exemplo 7.15 – A classe PessoaJuridica
5. Criar uma nova _Classe Java_ chamada **Funcionario**
* Siga o exemplo da ```pag.122``` -  Exemplo 7.16 – A classe Funcionario
6. Criar uma nova _Classe Principal Java_ chamada **UsaFuncionario** (está classe irá conter o método main)
* Siga o exemplo da ```pag.123``` -  Exemplo 7.17 – A classe UsaFuncionario


### Dicas

#### Criando propriedades (métodos get/set) de atributos de classe em Java

Isto irá facilitar muito sua vida.

1. Clique com o botão direito encima do nome da classe e selecione a opção **```Inserir Código...          Alt+Insert```**
2. Selecione a opção **```Getter e Setter...```**
3. Marque os atribuitos de deseja criar propriedades.
4. Marque a opção **Encapsular Campos**
5. Pressione o botao **Gerar**




## Teorias e exemplos práticos do livro sobre temas abordados nesta aula

### Herança

1. Herança - A classe **Object** (mãe de todas as classes em Java)
* (pag.120) Exemplo 7.11 – Listagem da classe Camisa
* (pag.121) Exemplo 7.12 – Listagem da classe UsaCamisa
2. Herança - exemplo da classe **Pessoa** (uso de extends)
* (pag.121) Exemplo 7.13 – A classe Pessoa
* (pag.122) Exemplo 7.14 – A classe PessoaFisica
* (pag.122) Exemplo 7.15 – A classe PessoaJuridica
3. UML de Herança
* (pag.123) Figura 7.8 – Diagrama de classes de acordo com a UML.
4. Herança de Herança - exemplo da classe **Funcionario** (que extende a classe *PessoaFisica*)
* (pag.122) Exemplo 7.16 – A classe Funcionario
* (pag.123) Exemplo 7.17 – A classe UsaFuncionario


### Qualificador

1. (pag.90) **Qualificador:** conhecido também pelo nome de modificador, define a visibilidade do método. ...

### Polimorfismo

1. 7.12 Polimorfismo
* (pag.125) Implementação do método **mostraClasse**, no final da página, em todoas as classes solicitadas
* (pag.126) Exemplo 7.21 – A Classe PessoaPolimorfa


