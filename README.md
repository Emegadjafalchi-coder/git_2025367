package git_2025367;

import java.util.Scanner;

public class Git_2025367 {
    public static void main(String[] args) {

        Scanner myKB = new Scanner(System.in);

        System.out.println("What is your name?");
        String myName = myKB.nextLine();

        System.out.println("Hello " + myName);

        System.out.println("What is your student ID?");
        String yourStudentID = myKB.nextLine();

        System.out.println("Good " + myName + ". Your student ID is: " + yourStudentID);

        myKB.close();
    }
}
        
