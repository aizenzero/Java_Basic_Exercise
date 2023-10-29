# Java_Basic_Exercise

import java.sql.SQLOutput;
import java.time.LocalDateTime;
import java.time.format.DateTimeFormatter;
import java.util.Scanner;
import java.util.WeakHashMap;

public class Main {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

//        Write a Java program that takes two numbers as input and displays the product of two numbers.
//                Test Data:
//        Input first number: 25
//        Input second number: 5
//        Expected Output :
//        25 x 5 = 125

//        System.out.print("Input first number: ");
//        int firstNumber = input.nextInt();
//
//        System.out.print("Input second number: ");
//        int secondNumber = input.nextInt();
//
//        int answer = firstNumber * secondNumber;
//
//        System.out.println(firstNumber+ " x "+secondNumber+" = "+answer);


//        Write a Java program to print the sum (addition), multiply, subtract, divide and remainder of two numbers.
//                Test Data:
//        Input first number: 125
//        Input second number: 24
//        Expected Output :
//        125 + 24 = 149
//        125 - 24 = 101
//        125 x 24 = 3000
//        125 / 24 = 5
//        125 mod 24 = 5

//        System.out.print("Input first number: ");
//        int firstNumber = input.nextInt();
//
//        System.out.print("Input second number: ");
//        int secondNumber = input.nextInt();
//
//        int add = firstNumber+secondNumber;
//        int sub = firstNumber-secondNumber;
//        int mul = firstNumber*secondNumber;
//        int div = firstNumber/secondNumber;
//        int mod = firstNumber%secondNumber;
//
//        System.out.println(firstNumber+" + "+secondNumber+" = "+add);
//        System.out.println(firstNumber+" - "+secondNumber+" = "+sub);
//        System.out.println(firstNumber+" * "+secondNumber+" = "+mul);
//        System.out.println(firstNumber+" / "+secondNumber+" = "+div);
//        System.out.println(firstNumber+" % "+secondNumber+" = "+mod);


//        Write a Java program that takes a number as input and prints its multiplication table up to 10.
//        Test Data:
//        Input a number: 8
//        Expected Output :
//        8 x 1 = 8
//        8 x 2 = 16
//        8 x 3 = 24
//...
//        8 x 10 = 80

//        System.out.print("Input a number: ");
//        int number = input.nextInt();
//
//        for(int i=0;i<=10;i++){
//            int answer = number * i;
//
//            System.out.println(number+" x "+i+" = "+answer);
//        }


//        . Write a Java program to compare two numbers.
//        Input Data:
//        Input first integer: 25
//        Input second integer: 39
//        Expected Output
//
//        25 != 39
//        25 < 39
//        25 <= 39

//        System.out.print("Input first integer: ");
//        int firstNumber = input.nextInt();
//
//        System.out.print("Input second integer: ");
//        int secondNumber = input.nextInt();
//
//        if(firstNumber!=secondNumber){
//            if(firstNumber<secondNumber){
//                System.out.println(firstNumber+ " != "+secondNumber);
//                System.out.println(firstNumber+" < "+secondNumber);
//                System.out.println(firstNumber+" <= "+secondNumber);
//            }else{
//                System.out.println(firstNumber+ " != "+secondNumber);
//                System.out.println(firstNumber+" > "+secondNumber);
//                System.out.println(firstNumber+" >= "+secondNumber);
//            }
//        }else{
//            System.out.println(firstNumber == secondNumber);
//        }

//        Write a Java program and compute the sum of an integer's digits.
//        Input Data:
//        Input an integer: 25
//        Expected Output
//
//        The sum of the digits is: 7

//        System.out.print("Input an integer: ");
//        int number = input.nextInt();
//
//        int sum = 0;
//
//        while (number != 0) {
//            sum += number % 10;
//            number /= 10;
//        }
//
//        System.out.println("Sum of the digits: " + sum);


//        Write a Java program to reverse a string.
//        Input Data:
//        Input a string: The quick brown fox
//        Expected Output
//
//        Reverse string: xof nworb kciuq ehT

//        System.out.print("Input a string words: ");
//        char [] word = input.nextLine().toCharArray();
//
//        for(int i = word.length -1;i>=0;i--){
//            System.out.print(word[i]);
//        }


//         Write a Java program to count letters, spaces, numbers and other characters in an input string.
//                Expected Output
//
//        The string is :  Aa kiu, I swd skieo 236587. GH kiu: sieo?? 25.33
//        letter: 23
//        space: 9
//        number: 10
//        other: 6

//        System.out.print("Input string words: ");
//        String word = input.nextLine();
//
//        int letter = 0;
//        int space = 0;
//        int num = 0;
//        int other = 0;
//
//        for (int i = 0; i < word.length(); i++) {
//            char ch = word.charAt(i);
//
//            if (Character.isLetter(ch)) {
//                letter++;
//            } else if (Character.isDigit(ch)) {
//                num++;
//            } else if (Character.isWhitespace(ch)) {
//                space++;
//
//            } else {
//                other++;
//            }
//        }
//
//            System.out.println("Letters: " + letter);
//            System.out.println("Spaces: " + space);
//            System.out.println("Numbers: " + num);
//            System.out.println("Other characters: " + other);



//        Write a Java program to create and display a unique three-digit number using 1, 2, 3, 4. Also count how many three-digit numbers are there.
//                Expected Output
//
//        123
//        124
//...
//
//        431
//        432
//        Total number of the three-digit-number is 24

//        int number = 0;
//
//        for(int i = 0; i<4;i++){
//            for(int j = 0;j<4;j++){
//                for(int k = 0;k<4;k++){
//
//                    if (i != j && j != k && k != i) {
//                        number++; // Increment the counter
//                        System.out.println(i + "" + j + "" + k);
//                    }
//                }
//            }
//        }
//        System.out.println(number);


//
//        Write a Java program to display system time.
//        Sample Output:
//
//        Current Date time: Fri Jun 16 14:17:40 IST 2017


//        LocalDateTime currentDateTime = LocalDateTime.now();
//
//        // Define the date and time format
//        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("E MMM dd HH:mm:ss z yyyy");
//
//        // Format and display the current date and time
//        String formattedDateTime = currentDateTime.format(formatter);
//        System.out.println("Current Date time: " + formattedDateTime);


//
//        Write a Java program to print odd numbers from 1 to 99. Prints one number per line.

//        for(int i=0;i<100;i++){
//
//            if(i%2!=0){
//                System.out.println(i);
//            }
//        }

//        Write a Java program to accept a number and check whether the number is even or not. Prints 1 if the number is even or 0 if odd.
//                Sample Output:
//
//        Input a number: 20
//        1

//        System.out.print("Input a number: ");
//        int number = input.nextInt();
//
//        if(number%2==0){
//            System.out.println(1);
//        }else{
//            System.out.println(0);
//        }


    }


}
