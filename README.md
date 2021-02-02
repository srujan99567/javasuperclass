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