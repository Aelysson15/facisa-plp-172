José Aelysson Dionísio de Souza – 1313080029
PLP – Problema do Diamante
O problema do diamante se caracteriza na impossibilidade de herança múltipla. Em java por exemplo que é uma linguagem que não permite essa prática.
Um bom exemplo de uma funcionalidade em OO do problema:
Um carro Gol com roda aro 15, sendo assim, se uma classe como GolNormal herda da classe GolAroQuinze, ela automaticamente herda o Aro 15.
Ex:
public class GolAroQuinze{
public void aroQunze(){
        System.out.println("Gol Aro 15");
}
}
public class GolNormal extends GolAroQuinze {
}
public class ProgramaDiamante{
public static void main(String[] args){
        GolNormal g1 = new GolNormal ();
         G1.aroQuinze();
}
}
O problema é que não podemos criar herança múltipla como herdar aro15 de um carro e liga leve de outo. Java não utilizar herança múltipla. Ele iria se confundir, se comportar de maneira inesperada e imprevisível.
No caso seria public Class GolDois extends GolAroQuinze, UnoLigaLeve{}
