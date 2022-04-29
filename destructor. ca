# destructor
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    class Program 
    {
    	public int age;
    	public string name;
    	Program(int age1,string name1)
    	{
    		age=age1;
    		name=name1;
    	}
    	int age1()
    	{
    		return age;
    	}
    	string name1()
    	{
    		return name;
    	}
    	~Program()
    	{
    	 Console.WriteLine("destructor called");
    	}
        public static void Main() 
        {
        	Program p1=new Program(100,"nikita");
        	Console.WriteLine(p1.age1());
        	Console.WriteLine(p1.name1());
            
        }
    }
}
