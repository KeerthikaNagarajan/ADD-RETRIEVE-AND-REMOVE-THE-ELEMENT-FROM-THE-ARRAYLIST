## Ex-9
## ADD,RETRIEVE AND REMOVE THE ELEMENT FROM THE ARRAYLIST
### Aim:
To write the java program to add, retrieve and remove the element from the ArrayList.

### Procedure:
* Create the class and declare the main method so that the JVM will identify the main program to run.
* Declare a variable to accept the arraylist input.
* To accept the inputs from user import Scanner and get the input and store them.
* To add elements to ARRAYLIST use add() to add elements to the list.
* Print the output after accepting all the inputs.
* The program will be executed after the compilation and results are printed.

### Code:
```
import java.util.ArrayList;
import java.util.Scanner;

public class Ex9 {
    public static void main(String[] args) {
        ArrayList<Integer> arr1=new ArrayList<Integer>();
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the size of array: ");
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            arr1.add(sc.nextInt());
        }
        System.out.println("Array: ");
        System.out.println(arr1);
        System.out.println("Retrieving an element: "+ arr1.get(1));
        System.out.println("Removing an element: "+arr1.remove(2));
        System.out.println("After removing: "+arr1);
    }
}
```

### Output:
<img width="188" alt="9" src="https://github.com/KeerthikaNagarajan/Java-Ex-9/assets/93427089/893fdce6-ba66-417d-a317-b7fdf3a5408a">

### Result:
Thus the program compile successfully.

