class Add{
	int a,b,c;
	public void add(int a,int b)
	{
		System.out.println(a+b);
	}
	public void add(int a, int b, int c)
	{
		System.out.println(a+b+c);
	}
}
public class Jala {
	public static void main(String[] args) {
		Add a = new Add();
		a.add(5,6);
		a.add(2,3,4);
	}
}
