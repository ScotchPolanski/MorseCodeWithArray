import java.util.Scanner;

public class MorseArray
{
    public static void main(String[] args)
    {
        do{
        System.out.println("");
        Scanner scanner = new Scanner(System.in);   	                                                                    // Scanner wird zugewiesen
        System.out.println("=== Morse Konverter ===");
        System.out.println("Eingabe: ");
        String ausgabe = scanner.nextLine();
        ausgabe = ausgabe.replace(" ", "");
        ausgabe = ausgabe.toLowerCase();                                                                                    // groß in klein
        System.out.println("Vor der Konvertierung: " + ausgabe);
        System.out.println("Nach der Konvertierung: ");
        Kodieren(ausgabe);
        System.out.println();
        System.out.println("Druecke Enter zum Wiederholen");
        try                                                                                                                 // try-catch Block (für Wiederholen bei [Enter])
        {
            System.in.read();
            System.in.skip(System.in.available());
        }
        catch(Exception e) {e.printStackTrace();}
        System.out.println();
        }while(true); 
    }
    static void Kodieren(String ausgabe)                                                                        // Funktion die Zeichenkette in Morsecode überführt (AUFGABENSTELLUNG)
    { 
        String Morsecodes[] = new String[26];

        Morsecodes[0] = ".- ";                                                                                       // A
        Morsecodes[1] = "-... ";                                                                                     // B
        Morsecodes[2] = "-.-. ";                                                                                     // C
        Morsecodes[3] = "-.. ";                                                                                      // D
        Morsecodes[4] = ". ";                                                                                        // E
        Morsecodes[5] = "..-. ";                                                                                     // F
        Morsecodes[6] = "--.";                                                                                       // G
        Morsecodes[7] = ".... ";                                                                                     // H
        Morsecodes[8] = ".. ";                                                                                       // I
        Morsecodes[9] = ".--- ";                                                                                     // J
        Morsecodes[10] = "-.- ";                                                                                     // K
        Morsecodes[11] = ".-.. ";                                                                                    // L
        Morsecodes[12] = "-- ";                                                                                      // M
        Morsecodes[13] = "-. ";                                                                                      // N
        Morsecodes[14] = "--- ";                                                                                     // O
        Morsecodes[15] = ".--. ";                                                                                    // P
        Morsecodes[16] = "--.- ";                                                                                    // Q
        Morsecodes[17] = ".-. ";                                                                                     // R
        Morsecodes[18] = "... ";                                                                                     // S
        Morsecodes[19] = "- ";                                                                                       // T
        Morsecodes[20] = "..- ";                                                                                     // U
        Morsecodes[21] = "...- ";                                                                                    // V
        Morsecodes[22] = ".-- ";                                                                                     // W
        Morsecodes[23] = "-..- ";                                                                                    // X
        Morsecodes[24] = "-.-- ";                                                                                    // Y
        Morsecodes[25] = "--.. ";                                                                                    // Z


        for (int i = 0;i<ausgabe.length(); i++)                                                                 // for - Schleife geht durch Buchstaben
        {
            if(ausgabe.charAt(i) == 'a')
            {
                System.out.print(Morsecodes[0]);
            }
            if(ausgabe.charAt(i) == 'b')
            {
                System.out.print(Morsecodes[1]);
            }
            if(ausgabe.charAt(i) == 'c')
            {
                System.out.print(Morsecodes[2]);
            }
            if(ausgabe.charAt(i) == 'd')
            {
                System.out.print(Morsecodes[3]);
            }
            if(ausgabe.charAt(i) == 'e')
            {
                System.out.print(Morsecodes[4]);
            }
            if(ausgabe.charAt(i) == 'f')
            {
                System.out.print(Morsecodes[5]);
            }
            if(ausgabe.charAt(i) == 'g')
            {
                System.out.print(Morsecodes[6]);
            }
            if(ausgabe.charAt(i) == 'h')
            {
                System.out.print(Morsecodes[7]);
            }
            if(ausgabe.charAt(i) == 'i')
            {
                System.out.print(Morsecodes[8]);
            }
            if(ausgabe.charAt(i) == 'j')
            {
                System.out.print(Morsecodes[9]);
            }
            if(ausgabe.charAt(i) == 'k')
            {
                System.out.print(Morsecodes[10]);
            }
            if(ausgabe.charAt(i) == 'l')
            {
                System.out.print(Morsecodes[11]);
            }
            if(ausgabe.charAt(i) == 'm')
            {
                System.out.print(Morsecodes[12]);
            }
            if(ausgabe.charAt(i) == 'n')
            {
                System.out.print(Morsecodes[13]);
            }
            if(ausgabe.charAt(i) == 'o')
            {
                System.out.print(Morsecodes[14]);
            }
            if(ausgabe.charAt(i) == 'p')
            {
                System.out.print(Morsecodes[15]);
            }
            if(ausgabe.charAt(i) == 'q')
            {
                System.out.print(Morsecodes[16]);
            }
            if(ausgabe.charAt(i) == 'r')
            {
                System.out.print(Morsecodes[17]);
            }
            if(ausgabe.charAt(i) == 's')
            {
                System.out.print(Morsecodes[18]);
            }
            if(ausgabe.charAt(i) == 't')
            {
                System.out.print(Morsecodes[19]);
            }
            if(ausgabe.charAt(i) == 'u')
            {
                System.out.print(Morsecodes[20]);
            }
            if(ausgabe.charAt(i) == 'v')
            {
                System.out.print(Morsecodes[21]);
            }
            if(ausgabe.charAt(i) == 'w')
            {
                System.out.print(Morsecodes[22]);
            }
            if(ausgabe.charAt(i) == 'x')
            {
                System.out.print(Morsecodes[23]);
            }
            if(ausgabe.charAt(i) == 'y')
            {
                System.out.print(Morsecodes[24]);
            }
            if(ausgabe.charAt(i) == 'z')
            {
                System.out.print(Morsecodes[25]);
            }
        }
    }
}
