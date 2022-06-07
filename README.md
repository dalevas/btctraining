//Write a Java program to get the strings as input from the user and push them to an array. Find the shortest word in the list of strings and display the same on the screen.

int nwords = scan.nextInt();
    String sentence = scan.nextLine();
    String shortestword = new String();
    String[] words = sentence.split("Atrocity", "Pensive", "Imperceptible", "Discordant");
    for (int i = 0; i < nwords; i++){
        if (shortestword.length() < words[i].length()){
            shortestword = words[i];
    
        }
    }
    System.out.printf(shortestword);
    
    
