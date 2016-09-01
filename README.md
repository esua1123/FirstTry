# FirstTry
Attempt number 1

import java.awt.*;

public class RectangleMods 
{
	public static void main(String[] args)
	{
		Rectangle box = new Rectangle(0,0,8,13);
		
		System.out.println(box);
		
		moreBoxes(box);
	}
	
	public static void moreBoxes(Rectangle box)
	{
		box.translate(8,0);
		System.out.println(box);
		
		box.translate(0,13);
		System.out.println(box);
		
		box.translate(-8,0);
		System.out.println(box);
	}
}
