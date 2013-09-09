Projects-Bianca-Arjoca
======================
package javaCapitolulII.Instructiuni;

public class InstructiuneaBreak {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		boolean b= false;
		eticheta: if ((int)(Math.random() *2)==0){
			b = true;
			break eticheta;
		}
		if (b)System.out.println("S-a executat break eticheta.");
		else
			System.out.println("Nu s-a executat break eticheta.");
	}

}
