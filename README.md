# javasuperclass
class A
{
	int a;
	int b;
	void sup(int x,int y)
	{
		a=x;
		b=y;	
	}
	void displayab()
	{
		System.out.println("a="+a+"b="+b);
	}
}
class B extends A
{
	int c;
	void sub(int x,int y,int z)
	{
		a=x;
		b=y;
		c=z;	
	}
	void displayabc()
	{
		System.out.println("a="+a+"b="+b+"c="+c);
	}
}
class C extends B
{
	int d;
	void awm(int x,int y,int z,int z1)
	{
		a=x;
		b=y;
		c=z;
		d=z1;
	}
	void displayabcd()
	{
		System.out.println("a="+a+"b="+b+"c="+c+"d="+d);
	}
}
class Superclass1
{
	public static void main(String args[])
	{
		A sr = new A();
		B ku = new B();
		C aw = new C();
		
		sr.sup(10,20);
		sr.displayab();
		ku.sup(15,20);
		ku.displayab();
		ku.sub(10,20,30);
		ku.displayabc();
		aw.awm(1,2,3,4);
		aw.displayabcd();
		aw.sub(3,4,5);
		aw.displayabc();

	}
}
pr builder initiated to github