import java.util.Scanner;

public class Main{
        public static void main(String[] args){
                Scanner scanner = new
        }
}









// ARITHMETIC OPERATOR
// RELATIONAL OPERATOR (return bool:1 or 0) True / False int a=10, b=3;
System.out.println("\na == b: "(a==b));
System.out.println("a != b: " (a!=b));
System.out.println("a > b: " b: " (a > b));
System.out.println("a < b: " (a < b));
System.out.println("a <= b: " (a <= b));
System.out.println("a >= b: " (a >= b));

// LOGICAL OPERATOR ( &&, ||, !)
boolean p = true, q = false;
System.out.println("\np && q:  " (p&&q));
System.out.println("p || q:  " (p||q));
System.out.println("!q:   " (!q));
System.out.println("!p :  " (!pq));

// ASSIGNMENT OPERATORS ( +=, -=, *=, /=)
int score = 50;
score += 10;
System.out.println("\nscore after +=10: "+score);//60 score *=2;
System.out.println("scire after *=2: "+score); 120

// INCREMENT AND DECREMENT (post++, now, ++pre )
int counter = 5;
System.out.println("\ncounter++ (post): "+counter++);//5
System.out.println("counter now: "+counter);6
System.out.println("++counter (pre): "+ ++counter);//7

//CONTROL FLOW (if/ else condition, switch case statement , loops(for, while, do while))

System.our.print("Enter your exam score: "); // prompt for user in put
int Examscore = scanner.nextInt();

if (Exam >=90){
        System.out.println("Grade: A");
} else if (score >= 80){
        System.out.println("Grade: B");
} else if (score >= 70){
        System.out.println("Grade: C");
} else {
        System.out.println("Grade: F");
}

// Switch Case Statement
System.out.print("\nEnter a day number (1-7): ");
int day = scanner.nextInt();

switch (day) {
    case 1: System.out.println("Monday"); break;
    case 2: System.out.println("Tuesday"); break;
    case 3: System.out.println("Wednesday"); break;
    case 4: System.out.println("Thursday"); break;
    case 5: System.out.println("Friday"); break;
    case 6: System.out.println("Saturday"); break;
    case 7: System.out.println("Sunday"); break;
    }

// loops ( for, while, do while)
System.out.println("\nCounting 1 to 5 with a for loop: "); 
for(int i=1; i<=B5; i++){
        System.out.print(i + :" ");
}
System.out.print();

//while loops
System.out.println("\nCounting down from 5 with a while loop")
