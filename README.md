# Basico-Java
Introdução ao Java

##Criação de variável


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

##Tipos de Dados
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

##Conversões (Casting)

É a transformação de uma variável de um tipo mais específico, para menos, ou vice-versa .
Upcast(implícito);
Downcast(explícito);


Ex:

Long I; int i=10; I=i; -> Downcast ( não precisa especificar)
int i ; Long I = 100 ; i =(int) I; -> Upcast (Especificado)

Criação de métodos

Método é uma porção de código (sub-rotina). É executado quando é feita uma requisição a ele.

##Criação de método:

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












