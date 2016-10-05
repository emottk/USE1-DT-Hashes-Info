#>>HASHES

Back when we were learning about arrays, we created a list of students that we wanted to keep track of. Let's say their first test grades just came in and we want to keep track of those as well.

	students = ["Rebecca", "Eamond", "Cynthia", "Peter", "Katherine"]
	test1 = [95, 86, 92, 90, 88]

Great! Now we have two arrays, one keeping track of students, and one keeping track of their grades. But this is tough - the grades aren't tied to the students in anyway, making to hard to keep track of who has what grade. 		
Ruby has a tool to make this process much easier (of course).		

Hashes, another datatype in Ruby, is a collection of **keys** and **values**. These keys work in the same way that indexing works in arrays.		
They are set up like this:

	hash = {key1 => value1, key2 => value2, key3 => value3}
	
Hashes are created using curly brackets. Each key is tied to its value using `=>`, also known as a hash rocket. Keys and their values can be any data type -- strings, integers, floats, even arrays or more hashes! Keys need to be unique values, so that when called only one value is returned. 		
We can think of hashes much like we think of dictionaries - it organizes data in a way that is easy to look up.		

Let's get back to our student example. 		
Now we can associate our grades with the students that earned them!		

	students_grades = {"Rebecca" => 95, "Eamond" => 86, "Cynthia" => 92, "Peter" => 90, "Katherine" => 88}
	
Now if we want to know what Rebecca received on her first test, we can call her as a key and get the grade as the value!

	students_grades["Rebecca"]
		>> 95

We access a value in the same way that we access an index in an array - using hard brackets after the name of the hash. 		

Now this set of student names and grades is much more useful!		

With a partner, come up with 5 different examples of things that could be organized with hashes!

