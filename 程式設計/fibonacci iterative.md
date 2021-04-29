

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

![fibint](https://user-images.githubusercontent.com/71476321/116516394-26253980-a900-11eb-9a40-55175f1486a4.PNG)

