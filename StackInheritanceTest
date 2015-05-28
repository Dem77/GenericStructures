
public class StackInheritanceTest 
{

	public static void main(String[] args) 
	{
		StackInheritance <Integer> stack = new StackInheritance <Integer> ();
		stack.push(-1);
		stack.print();
		stack.push(0);
		stack.print();
		stack.push(1);
		stack.print();
		stack.push(1);
		stack.print();
		stack.push(5);
		
		try
		{
			int removedItem;
			
			while (true)
			{
				removedItem = stack.pop();
				System.out.printf("\n%d popped\n", removedItem);
				stack.print();
			}
		}
		catch (EmptyListException e)
		{
			e.printStackTrace();
		}
	}

}
