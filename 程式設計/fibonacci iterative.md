

	public class Fibonacci {


		public int fibInt(int n) {
			if(n <= 1) {
				return n;
			}
			int fib = 1;
			int prevFib = 1;

			for(int i=2; i<n; i++) {
				int temp = fib;
				fib+= prevFib;
				prevFib = temp;
			}
			return fib;
		}



		public static void main(String args[]) {
			Fibonacci fib = new Fibonacci();

			System.out.println(fib.fibonacciIterative(5));

		}
	}


