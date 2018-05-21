# Problem-4
public class x_testing {

    public static void main(String[] args) {
		System.out.println("i lik slep ;-}");
		
		for(int i = 101; i < 1000; i++) {
			for(int k = 101; k < 1000; k++) {
				
			String num = String.valueOf(i * k);
			int i1 = 0;
			int i2 = num.length() - 1;
			
			for (int j = num.length(); j > 0; j--) {
				if(num.charAt(i1) == num.charAt(i2)) {
				i1++;
				i2--;
				} else {
					break;
				}
				System.out.println("true " + i * k);
				}
			}
		}
    }
}
