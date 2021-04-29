
	public class Fibonacci {
	

	public int fibInt(int n) {
		if(n <= 1) {
			return n;
		}
		return fibInt(n-1) + fibInt(n-2);
	}
	
	
	
	public static void main(String args[]) {
		Fibonacci fib = new Fibonacci();
		
		System.out.println(fib.fibInt(5));
	
	}
}

![fibint](https://user-images.githubusercontent.com/71476321/116516905-c8452180-a900-11eb-92c3-b6b92fe699e2.PNG)
