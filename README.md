In the same example take input for all form parameters and display on the browser


	String courses[]=request.getParameterValues("Course");
		for(int i=0;i<courses.length;i++)
		{
			out.println("Your courses are: <b>"+courses[i]+"</b>" );
		}
		
Write the difference between ServletConfig/ServletContext
