# java
package saurabh_sukla;


public class Box {
	int length,breadth,height;
	void setdimension(int l, int b,int h)
	{
		length = l;
		breadth = b;
		height = h;		
	}
	void showdimension()
	{
		System.out.println("l="+length);
		System.out.println("b="+breadth);
		System.out.println("h="+height);

	}

	public static void main(String[] args) {
		Box newbox = new Box();
		newbox.setdimension(15,10,5);
		newbox.showdimension();

	}

}
