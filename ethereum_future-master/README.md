# ethereum_future
This is the Code for "Ethereum Future Prices" by Siraj Raval on Youtube


This is the code for [this](https://youtu.be/G5Mx7yYdEhE) video on Youtube by Siraj Raval on predicting cryptocurrency prices. 


Download [juypter](http://jupyter.org/) and run it via 'jupyter notebook' in terminal 
public class JavaExample {
   public static void main(String []args) {
	String str[] = { "Ajeet", "Steve", "Rick", "Becky", "Mohan"};
	String temp;
	System.out.println("Strings in sorted order:");
	for (int j = 0; j < str.length; j++) {
   	   for (int i = j + 1; i < str.length; i++) {
		// comparing adjacent strings
		if (str[i].compareTo(str[j]) < 0) {
			temp = str[j];
			str[j] = str[i];
			str[i] = temp;
		}
	   }
	   System.out.println(str[j]);
	}
   }
}
