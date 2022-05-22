# Tables-program-by-using-java
public class Table {

	public static void main(String[] args) {
		// creating tables by using scanner class
		Scanner input = new Scanner(System.in);
		System.out.println("Enter Number :");
		int N = input.nextInt();
		for(int n=1;n<=10;n++) {
			System.out.printf( " %d x %d = %d \n ",N,n,N*n);
		}
		input.close();

	}

}
