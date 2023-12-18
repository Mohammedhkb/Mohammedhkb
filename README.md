import java.util.Scanner;

public class ToDoList {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Declare variables for five tasks
        String task1, task2, task3, task4, task5;

        // Prompt user for each task
        System.out.println("Enter your first task:");
        task1 = scanner.nextLine();
        System.out.println("Enter your second task:");
        task2 = scanner.nextLine();
        System.out.println("Enter your third task:");
        task3 = scanner.nextLine();
        System.out.println("Enter your fourth task:");
        task4 = scanner.nextLine();
        System.out.println("Enter your fifth task:");
        task5 = scanner.nextLine();

        // Print the list of tasks
        System.out.println("\nYour To-Do List:");
        System.out.println("1. " + task1);
        System.out.println("2. " + task2);
        System.out.println("3. " + task3);
        System.out.println("4. " + task4);
        System.out.println("5. " + task5);

        scanner.close();
    }
}
