# integral
import java.util.Locale;
import java.util.Random;

public class integral {

	
	
	public static void main(String[] args) {
		// x karenin -5 ile 5 arasındaki   integrali
        double alan=0.0000;
		double altdeger = -5.0000;
		double h= 0.0001;
		int ustdeger = 5;
		
		while(altdeger <=ustdeger) {
		alan += Math.pow(altdeger, 2)*h;
		altdeger+=h;
	}
     System.out.println("Bu integralin sonucu:"+ alan);
}
}
