# FirstTry
Attempt number 1

import java.awt.*;

public class FourRectanglePrinter 
{
	public static void main(String[] args)
	{
		Rectangle box = new Rectangle(0,0,8,13);
		
		System.out.println(box);
		
		box.translate(8,0);
		System.out.println(box);
		
		box.translate(0,13);
		System.out.println(box);
		
		box.translate(-8,0);
		System.out.println(box);
		
	}
}
