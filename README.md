# Complete-your-adventure-E2
LSU encounter engineering design project
package project_4;/*
 * To change this license header, choose License Headers in Project Properties.
 * import java.util
 * and open the template in the editor.
 */
package project_4;
import java.util.*;
/**
 *
 * @author eadam38
 */
public class Project_4 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        System.out.print("Welcome to Intergalactic Space Adventures!");
        System.out.print("What is your name?");
        Scanner user = new Scanner(System.in);
        String name = user.next();
        System.out.println("Welcome"+ name);
        System.out.print("Do you want to enter the ride?");
        int a = 3;
        System.out.print("if yes enter 1");
        System.out.print("if no enter 2");
        Scanner answerone = new Scanner(System.in);
        answerone.close();
        
        a = answerone.nextInt();
        
        if (a == 2)
            System.out.print ("Thank you for your time");
        else if (a == 1)
            System.out.println("Thank you for choosing Intergalactic Space "
                    + "Adventures. Your ride will begin shortly. What is your destination? "
                    + "Enter 1 for Mars or 2 for Europa");
        else
        System.out.println("error");
        
        Scanner answertwo = new Scanner(System.in);
        answertwo.close();
        
        int b = answertwo.nextInt();
        if (b == 1)
            System.out.print ("Your destination is set to Mars, keep all hands and objects "
                    + "inside the spacecraft.");
        
        else if (b == 2)
            System.out.println("Your destination is set to Europa, keep all hands and objects inside the spacecraft.");
        else
        System.out.println("error");
