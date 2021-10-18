# massivkobeitu
public static void main(String[] args) {
        int [][]a=new int[3][3];
        int [][]b=new int[3][3];
        //2 massiv razmer berdik
        Random r=new Random();
        //random kocu
        System.out.println("birinshi massive");
        for (int i=0;i<3; i++) {
            for (int j=0;j<3; j++) {
                a[i][j]=r.nextInt(100); //a massivin random sanmem toltiru
                System.out.print(a[i][j] + "\t");

            }
            System.out.println();
        }
        System.out.println("2 massiv");
        for (int i=0;i<3; i++) {
            for (int j=0;j<3; j++) {
                b[i][j]=r.nextInt(100);
                System.out.print(b[i][j] + "\t");

            }
            System.out.println();
        }
        System.out.println("2 massiv tikeley kobeitu");
        int c;
        //zhana ainnymalyny kosu
        for (int i=0;i<3; i++) {
            for (int j = 0; j < 3; j++) {
                c=a[i][j]*b[i][j];
                // 2 mastin saikes el kobeitui zhana ainimaliga ten
                System.out.print(c + "\t"); //resultatty rorsetu
            }
            System.out.println();
        }
    }

}

