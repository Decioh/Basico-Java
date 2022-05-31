# Basico-Java
Introdução ao Java

## Criação de variável


Variável:
tipos:
Instância : objeto
Classe : classe
local : dentro de métodos
Parâmetro : na assinatura do método 

Criação de variável:
<?Visibilidade?><?Modificado?r>Tipo nome<?=valor inicial?>
V: public, protected e private
M: static e final
T: tipo de dado: 
N: Nome da variável
Vi: Um valor inicial(opcional)

O que está entre interrogações é opcional.

## Tipos de Dados
Estática(fortemente tipada) precisamos escolher apenas um tipo de variável.
Dinâmica(fracamente tipada)
Primitivo - int
Composto - Struct
Op de tipos
Texto
Número
Lógico
Objeto

Byte b= 10; //Byte
Short s=1;
Long l = 14;
Float f=1.5;
Double d= 2.5;
// char c='Aeeeeee';
char c='a';
String st= "Décio";

boolean boo = true; // false;

## Conversões (Casting)

É a transformação de uma variável de um tipo mais específico, para menos, ou vice-versa .
Upcast(implícito);
Downcast(explícito);


Ex:

Long I; int i=10; I=i; -> Downcast ( não precisa especificar)
int i ; Long I = 100 ; i =(int) I; -> Upcast (Especificado)

Criação de métodos

Método é uma porção de código (sub-rotina). É executado quando é feita uma requisição a ele.

## Criação de método:

<?Visibilidade?><?Modificado?r>Tipo nome<?=valor inicial?>

V: public, protected e private
T: Concreto ou abstrato
M: static e final
R: tipo de dado ou “Void”  
N: Nome da variável
P: parâmetros que pode receber
E: exceções que pode lançar
C: Código que possui e vazio

Ex:

public Static R N (P){
…
…
…
}

public int VerificarDistância (int coordenada 1, int coordenada 2){
Corpo do método…
}
chamar o método:

nome_da_classe.nome_do_metodo(...);

math.random(); ou  Math.sqrt(4);

Assinatura do método:
para o método:
public double calcularTotalVenda(double preco1, double preco2, double preco3){
…
}

Assinatura = nome +(parâmetros);
Ex:
calcularTotalVenda(double preco1,double preco2, double preco3);

Passagem de parâmetro:
Por referência(endereço)
Por valor(cópia)

int i = 10;
public void fazerAlgo( int i) {

i = i + 10;

System.out.println(“Valor de i dentro : “ + i); // i = 20 valor apenas dentro do método
}
System.out.println(“Valor de i fora: ” + i); // i = 10 valor fora do método

## Collections:
 import java.util.ArrayList
 import java.util.List
 
 List notas = new ArrayList(); //Forma comum antes do java 5
 List<Double> notas = new ArrayList<>();
  List<Double> notas = Array.asList(7d, 8.5d, 9.3d, 5d, 7d, 0d, 3.6) -> Não permite adicionar nem remover da lista;
  
 A estrutura de coleções fornece as duas interfaces que definem várias coleções e classes que as implementam.
  Comandos:
  [x] Iniciar
 
https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/List.html
 
[x] Generics
 
[x] Diamond Operator
 
https://www.baeldung.com/java-diamond-operator
 
[x] toString() - Representação em string de um objeto 
 
[x] indexOf() - Posição de um elemento
 
[x] add() - Adiciona xxxx.add(int posição, int data);
 
[x] set() - Substiti xxx.set(int posição, float data);
 
[x] contains() - boolean, se contem ou não um dado passado xxxx.contains(Double dado);
 
[x] get() - apresenta uma nota na posição y xxx.get(y)
 
[x] Collections.min() - minimo da lista
 
[x] Collections.max() - maximo da lista
 
[x] iterator() - Iterator<tipo de dado> iterator = xxxx.iterator();
 
[x] iterator.hasNext() - retorna true ou false, se existir proximo elemento
 
[x] iterator.next() - próximo na lista;
 
[x] iterator().remove() - remove da lista
 
[x] size() - quantidade de elementos xxxx.size();
 
[x] remove() - remove posição ou objeto;
 
[x] clear() - Limpa a lista
 
[x] isEmpty() - Booleano, para vazia(true) ou cheia(false)
 
 Interface comparable - compara strings;
 













