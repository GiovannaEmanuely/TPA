import java.util.Scanner;
public class signo {
public static void main(String [] args){
    Scanner in = new Scanner(System.in);

    int m,d;

    System.out.println("Insira seu mes de aniversario:");
    m = in.nextInt();

    System.out.println("insira o dia do seu aniversario");
    d = in.nextInt();

    switch (m) {
        case 1:
            if (d>19 && d<32) {
                System.out.println("Aquario");
            } else if (d>0 && d<20) {
                System.out.println("capricornio");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 2:
            if(d>0 && d<19){
                System.out.println("Aquario");
            }else if(d>18 && d<30) {
                System.out.println("Peixes");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 3:
            if(d>0 && d<21){
                System.out.println("Peixes");
            }else if(d>20 && d<31){
                System.out.println("Aries");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 4:
            if(d>0 && d<20){
                System.out.println("aries");
            }else if(d>19 && d<31){
                System.out.println("Touro");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 5:
            if(d>0 && d<21){
                System.out.println("Touro");
            }else if(d>20 && d<32){
                System.out.println("Gemeos");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 6:
            if(d>0 && d<21){
                System.out.println("Gemeos");
            }else if(d>20 && d<31){
                System.out.println("Cancer");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 7:
            if(d>0 && d<23){
                System.out.println("cancer");
            }else if(d>22 && d<32){
                System.out.println("Leao");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 8:
            if(d>0 && d<23){
                System.out.println("Leao");
            }else if(d>22 && d<32){
                System.out.println("Virgem");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 9:
            if(d>0 && d<23){
                System.out.println("Virgem");
            }else if(d>22 && d<31){
                System.out.println("Libra");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 10:
            if(d>0 && d<23){
                System.out.println("Libra");
            }else if(d>22 && d<32){
                System.out.println("Escorpiao");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 11:
            if(d>0 && d<22){
                System.out.println("Escorpiao");
            }else if(d>21 && d<31){
                System.out.println("Sagitario");
            }else{
                System.out.println("dia invalido");
            }
            break;
        case 12:
            if(d>0 && d<22){
                System.out.println("Sagitario");
            }else if(d>21 && d<32){
                System.out.println("capricornio");
            }else{
                System.out.println("dia invalido");
            }
            break;
        default:
            System.out.println("mes invalido");
            break;
    }
    in.close();
}
}


