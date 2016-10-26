# HomeTask1
L1T1

package lesson1;

public class Main {

	public static void main(String[] args) {

		Cat[] catArray = new Cat[5];
		catArray[0]=new Cat("Vasyz",15,32.5,"Grey");
		catArray[1]=new Cat("Mysya",2,12.12,"Blue");
		catArray[2]=new Cat("Zozya",5,3.2,"Red");
		catArray[3]=new Cat("Piston",25,132.5,"Black");
		catArray[4]=new Cat("Zaraza",1,5.3,"Green");
		
		for(int i = 0;i<catArray.length;i++){
			System.out.println(catArray[i]);
		}
	}

}
