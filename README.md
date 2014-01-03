praveen
=======
public class PyramidOfDoom { 
    public static void main(String[] args) 
        int k = 2; 
        int totalWidth = 8; 
        for (int row = 1; row <= totalWidth; row++) { 
            for (int col = 1; col <= totalWidth; col++) { 
                if (col <= totalWidth - row) { 
                    System.out.print(" "); 
                } else { 
                    System.out.print(k);; 
                } 
            } 
            System.out.println(); 
        } 
    } 
}
