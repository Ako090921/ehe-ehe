 public static void main(String[] args)
    
    {
        Scanner choice = new Scanner(System.in);
        Scanner menu = new Scanner(System.in);
        
        System.out.println("ARE YOU TOMGUTS NA?");
        System.out.println("Fastfood Chains Nearby\n1.junebee\n2.rogerhaker\n3.leonyscusine");
        System.out.println("\nPlease Input Your Choice:");
        int FastF = choice.nextInt();
        
        
        
        if(FastF == 1)
            {
                System.out.println("junebee Menu");
                System.out.println("1. Sinigang na 87 sa komu");
                System.out.println("2. Okay class");
                System.out.println("3. Cathy papasukin mo na sila");
                System.out.println("4. Von salamat ah");
                System.out.println("5. Hello, Stem 7a naririnig ba?");
            
                System.out.println("Enter Your Choice:");
                int menuF = menu.nextInt();
            
        switch (menuF)
            {
                case 1:
                    System.out.println("You ordered Sinigang na 87 sa komu");
                    break;
                case 2:
                    System.out.println("You ordered Okay class");
                    break;
                case 3:
                    System.out.println("You ordered Cathy papasukin mo na sila");
                    break;
                case 4:
                    System.out.println("You ordered Von salamat ah");
                    break;
                case 5:
                    System.out.println("You ordered Hello, Stem 7a naririnig ba?");
                    break;
                default :
                    System.out.println("tanga wala ganyang number bobo");
            }
            }
        
        
        
        if(FastF == 2)
            {
                System.out.println("rogerhaker Menu");
                System.out.println("1. Hello class? bakit walang sumasagot?");
                System.out.println("2. Good Morning class loud and clear na ba?");
                System.out.println("3. *inaudible voice*");
                System.out.println("4. Ok~ so");
                System.out.println("5. Any volunteer? Yung iba naman");
            
                System.out.println("Enter Your Choice:");
                int menuF = menu.nextInt();
            
        switch (menuF)
            {
                case 1:
                    System.out.println("You ordered Hello class? bakit walang sumasagot?");
                    break;
                case 2:
                    System.out.println("You ordered Good Morning class loud and clear na ba?");
                    break;
                case 3:
                    System.out.println("You ordered *inaudible voice*");
                    break;
                case 4:
                    System.out.println("You ordered Ok~ so");
                    break;
                case 5:
                    System.out.println("You ordered Any volunteer? Yung iba naman");
                    break;
                default :
                    System.out.println("tanga wala ganyang number bobo");
            }
            }
         
         
         
        if(FastF == 3)
            {
                System.out.println("leonyscusine Menu");
                System.out.println("1. Eto si johnson maagang nagbakasyon");
                System.out.println("2. Okay goodmorning class, let's have your attendance first");
                System.out.println("3. Isa ka pa , Canto nag mamadali ka kahit tinapa hindi magpapabalot sa papel mo. At hindi maintindihan ang ibang sulat mo, 8 lang ang tama mo.");
                System.out.println("4. Princess, parang galing sa ospital ang concept note mo , like yung paper ni Hanopol.");
                System.out.println("5. Parang pangarera ang mukha mo, baka gusto mong palitan ang picture mo ng truck? Gets mo Banaga?");
            
                System.out.println("Enter Your Choice:");
                int menuF = menu.nextInt();
            
        switch (menuF)
            {
                case 1:
                    System.out.println("You ordered Eto si johnson maagang nagbakasyon");
                    break;
                case 2:
                    System.out.println("You ordered Okay goodmorning class, let's have your attendance first");
                    break;
                case 3:
                    System.out.println("You ordered Isa ka pa , Canto nag mamadali ka kahit tinapa hindi magpapabalot sa papel mo. At hindi maintindihan ang ibang sulat mo, 8 lang ang tama mo.");
                    break;
                case 4:
                    System.out.println("You ordered Princess, parang galing sa ospital ang concept note mo , like yung paper ni Hanopol.");
                    break;
                case 5:
                    System.out.println("You ordered Parang pangarera ang mukha mo, baka gusto mong palitan ang picture mo ng truck? Gets mo Banaga?");
                    break;
                default :
                    System.out.println("tanga wala ganyang number sa pag pipilian bobo");
            }
            } 
    if (FastF>3 || FastF<1)
        {
        System.out.println("INVALID YAN TSK: CLOSE KO MUNA TANGA MO TSK");
        System.exit(0);
        }
    System.out.println("\nTHANK YOU!");
    
    }
                
    
    
}
