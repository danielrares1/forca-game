public class JogoDaForca {

    public static void main(String[] args) {

        Scanner read = new Scanner(System.in);

        String palavra = "palmeiras";
        String palavraMascarada = palavra;

        int erros = 0, acertos = 0, mistake = 0;
        char letra;

        char[] forca = palavra.toCharArray();

        //Mascarando palavra principal
        for (char underline : palavra.toCharArray()) {
            palavraMascarada = palavraMascarada.replace(underline, '_');
        }

        //Vetor da palavra mascarada
        char[] vetorMascarado = palavraMascarada.toCharArray();

        //Enquanto para testar os erros
        while (erros < 7) {

            System.out.println("Digite uma letra");
            letra = read.next().charAt(0);

            //Comparando letra do vetor mascarado com a palavra de entrada
            for (int j = 0; j < palavra.length(); j++) {
                if (letra == forca[j]) {
                    vetorMascarado[j] = letra;
                    acertos++;
                }
            }

            System.out.println(vetorMascarado);
            System.out.println(acertos);

        }
    }

}
