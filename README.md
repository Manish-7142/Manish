import java.util.*;
public class Main {
	public static void main(String[] args) {
		Scanner ab = new Scanner (System.in);
		System.out.print("Enter the number of table : ");
		int num = ab.nextInt();
		for (int i = 1;i<=10;i++){
			System.out.println(num+ " × " +i+ " = " +num*i   );
		}
		
	}
}
