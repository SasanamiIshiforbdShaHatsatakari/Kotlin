fun main() {
    // Variáveis - guarda valores
    // Dois pontos para criar
    // var - mutável - seu valor pode ser auterado
    // val - mutavel só que n -seu valor n pode ser auterado
    // TIPOS DE VÁRIAVEIS(principais🙂)
    // String - uma variavel que armazena objetos no geral(caracteres)
    // dentro de aspas
    // boolean - verdadeiro ou falso, sim ou não, 1 ou 0
    // Int - números inteiros
    //Float - números reais ( com um número baixo de casas decimais)
    //Double - números reais tbm (número alto de casas decimais)
    //Long - números reais (número altissimo de casas decimais(números completos))
   
 //Exercicío

//Faça uma apresentação de si mesmo dizendo nome, idade ,país e cidade atráves de variáveis
var noelMeDaUmNome:String = Kaue
var:Int quantoDeVelhidao = 13 
var:String países = Brasil
var:String city = saoPaulo
println("O meu nome que não é da minha história é $noelMeDaUmNome , a minha idade em azul é $quantoDeVelhidao , moro no $países em uma cidade desconhecida mas que é conhecida com o nome de $city \n")

}



 // = --> dar valor a algo
    //operadores lógicos
    //- --> subtração
    //+ --> adição
    //* -->multiplicação
    // / -->divisão
    // % -->módulo
    /*println(40+70)
    println(40-70)
    println(40*70)
    println(40/70)
    println(7%2)
    */
    //operadores relacionais
    //== --> igual a algo
    //!= --> diferente a algo
    // > --> maior que
    // < -->menor que
    // >= --> maior ou igual a
    // <= --> menor ou igual a
    //
    //++ -->adiciona 1
    //-- -->subtrai 1
    //
    //
    //var num = 0
    //num++
    //println(num)
    //
    //
    //if e else
    //estrutura:
    //
    //if(condição){
    //ações
    //}else{
    //ação
    //}
    /*
      var dia= 21
    
    if(dia<=21){
        println("Hoje tem aula")
    }else{
        println("Hoje não tem aula")
        */
        //if e else composto
        //estrutura:
        //if(condição){
       //ações
       //}else if (condição){
       //ação}else{
       //ação}else if (condição){
       //ação}else{
       //ação}
       //...
       var valorEmReaisDaMinhaVida=1
    if(valorEmReaisDaMinhaVida <= 0){
        println("tu ta morto")
    }else if (valorEmReaisDaMinhaVida == 1){
        ("tu ta morrendo!!")
    }else if(valorEmReaisDaMinhaVida == 2){
        println("ce não tá muito bem, se cuida ae")
    }else if (valorEmReaisDaMinhaVida == 3){
        println("tu ta ok, só come miojo")
    }else if (valorEmReaisDaMinhaVida == 4){
        println("ce ta de boa, vai curtir")
    }else{
        println("tu tá ÓTIMO!!! Parabéns!")
    }

fun main() {
  //1 - faça um programa com duas váriaveis que representa cada uma, um número.
  //ele(programa) deve verificar qual dos dois é o maior número e imprimi-lo no console
  //2 - faça um programa que verifique se o valor de uma váriavelé maior, igual ou menor que 0
    /*
    var sd = 13
    var ds = 16
    if(sd > ds){
        println("Maior: $sd \n")
        
    }else 
    println("Maior: $ds \n")
}

*/
   /* var din = 7
     if((din > 0) {
        println("A váriavel $din é maior que zero")
        
    }else if(din = 0) {} 
    println("A váriavel $din é igual a zero") 
    
    }else println("A váriavel $din é menor zero") 
    */
    //Operadores lógicos 
    //&& -> e
    // || -> ou
   
   /* var corações = 0
    var vidas = 0
    
    if(corações <= 0 && vidas <= 0){
        println("press f, sua vida é uma falha ")
        
    } else { 
        println("o jogo vai ser reiniciado ")
    }*/
  /*var corações = 0
    var vidas = 2
    
    if(corações <= 2 || vidas <= 3){
        println("press f, sua vida é uma falha ")
        
    } else { 
        println("o jogo vai ser reiniciado ")
    }*/
    //v - verdadeiro
    //f - falso
    //
    //  &&
    //vv - executa
    //vf - não executa
    //fv - não executa
    //ff - não executa
    //
    //  ||
    //vv - executa
    //vf - executa
    //fv - executa
    //ff - não executa
    
    //When - quando
    var mes = 3
    when(mes){
        1 -> {println("Janeiro")}
        2 -> {println("Fevereiro")}
        3 -> {println("Março")}
        4 -> {println("Abril")}
        5 -> {println("Maio")}
        6 -> {println("Junho")}
        7 -> {println("Julho")}
        8 -> {println("Agosto")}
        9 -> {println("Setembro")}
        10 -> {println("Outubro")}
        11 -> {println("Novembro")}
        else -> {println("Dezembro")}
    }
}

fun main() {
  //1 - faça um programa com duas váriaveis que representa cada uma, um número.
  //ele(programa) deve verificar qual dos dois é o maior número e imprimi-lo no console
  //2 - faça um programa que verifique se o valor de uma váriavelé maior, igual ou menor que 0
    /*
    var sd = 13
    var ds = 16
    if(sd > ds){
        println("Maior: $sd \n")
        
    }else 
    println("Maior: $ds \n")
}

*/
   /* var din = 7
     if((din > 0) {
        println("A váriavel $din é maior que zero")
        
    }else if(din = 0) {} 
    println("A váriavel $din é igual a zero") 
    
    }else println("A váriavel $din é menor zero") 
    */
    //Operadores lógicos 
    //&& -> e
    // || -> ou
   
   /* var corações = 0
    var vidas = 0
    
    if(corações <= 0 && vidas <= 0){
        println("press f, sua vida é uma falha ")
        
    } else { 
        println("o jogo vai ser reiniciado ")
    }*/
  /*var corações = 0
    var vidas = 2
    
    if(corações <= 2 || vidas <= 3){
        println("press f, sua vida é uma falha ")
        
    } else { 
        println("o jogo vai ser reiniciado ")
    }*/
    //v - verdadeiro
    //f - falso
    //
    //  &&
    //vv - executa
    //vf - não executa
    //fv - não executa
    //ff - não executa
    //
    //  ||
    //vv - executa
    //vf - executa
    //fv - executa
    //ff - não executa
    
    //When - quando
    var mes = 3
    when(mes){
        1 -> {println("Janeiro")}
        2 -> {println("Fevereiro")}
        3 -> {println("Março")}
        4 -> {println("Abril")}
        5 -> {println("Maio")}
        6 -> {println("Junho")}
        7 -> {println("Julho")}
        8 -> {println("Agosto")}
        9 -> {println("Setembro")}
        10 -> {println("Outubro")}
        11 -> {println("Novembro")}
        else -> {println("Dezembro")}
    }
}

fun main() {
//laços de repetição - repetem uma ação quando determinada condição for verdadeira 
//
//while -> enquanto
//
//do..while -> faça..enquanto
//
//
//for -> para
//
//repeat -> repita
//
//
// -------------------------
//
//
//
//
//
// repeat - repita
// estrutura do repeat
//
// repeat(vezes que vai ser repetido){
// ações
// }
/*repeat(10){
    println("por ordem dos peaky blinders")
  }
}
 */
//laço While - enquanto
//
//estrutura while
//
//while(condição){
//ações
//}
/*var dia = 360
while(dia <= 365){
    println(dia)
    dia++
  }
}
*/
    
    //laço do..while - faça enquanto
    //
    //executa a ação enquanto for verdadeira
    //
    // estrutura do do..while
    // 
    //  do{
    //  ação
    //  }while(condição) 
    /*
    var dia = 360
    
    do{
        println(dia)
        dia++
    }while(dia <= 365)
}
*/
//exercício - faça um programa,utilizando while,
//que mostre no console os números de 0 a 100
/*var dia = 0;
    while(dia <= 100){
        println(dia)
        dia++
    }*/

//exercício - faça um programa utilizando 2 variaveis, e mostre no console, os números de 0 até N,
//onde N(você decide o valor) é o valor de uma das variáveis

/*var um = 0
var N = 229
    
 while(um <= N){
        println(um)
        um++

 }
}
*/    
