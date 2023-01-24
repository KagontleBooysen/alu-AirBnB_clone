![HBNB-HolbertonAirbnb](https://user-images.githubusercontent.com/106469425/213869129-3cc12e0a-16f9-4f15-ab07-acfb0cd90ba6.png)


<b>0x00.AirBnB Clone - The Console</b>

<b><h3>Functionalities of this command interpreter:</h3></b>
<ol>
<li>Create a new object (ex: a new User or a new Place)</li>
<li>Retrieve an object from a file, a database etc...</li>
<li>Do operations on objects (count, compute stats, etc...)</li>
<li>Update attributes of an object</li>
<li>Destroy an object</li>
</ol>
<b><h3> Environment</h3> </b>

This project is interpreted/tested on Ubuntu 20.04 LTS using python3 (version 3.4.3)

<b><h3>Installation</b></h3>
<ol>
<li>Clone this repository: git clone"https://github.com/KagontleBooysen/AirBnB_clone.git"</li>
<li>Access AirBnb directory: cd AirBnB_clone</li>
<li>Run hbnb(interactively): ./console and enter command</li>
<li>Run hbnb(non-interactively): echo "" | ./console.py</li>
</ol>

<b><h3>Description</b></h3>

This team project is part of the year two curriculum. It is the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management,and the base classes for the storage of this data.

<b><h3>Console and Command Usage</h3></b>

The console is a Unix shell-like command line user interface provided by the python CmdModule It prints a prompt and waits for the user for input, for our project we used (hbnb)
<table>
<tr>
<td><b>Command</b</td>
<td><b> Example</b></td>	
</tr>
<tr>
<td> Display commands help</td>
<td>(hbnb) help	</td>
</tr>
<tr>
<td>Create object (prints its id)</td>
<td>(hbnb) create )</td>	
</tr>
<tr>
<td>Destroy object</td>
<td>(hbnb) destroy or (hbnb) .destroy()</td>
</tr>
<tr>
<td>Show object</td>
<td>(hbnb) show or (hbnb) .show()</td>	
</tr>
<tr>
<td>Show "all" objects or instances class</td>
<td>(hbnb) all or (hbnb) all</td>	
</tr>
<tr>
<td>Run console</td>
<td>./console.py</td>	
</tr>	
<tr>
<td>Quit console</td>
<td>(hbnb)quit</td>	
</tr>		
</table>	
Help command example

(hbnb) help

<b><h3> Documented commands (type help ):</h3></b>

EOF all count create destroy help quit show update

<b><h3>Class Models Used</b></h3>

<table>
<tr>
<td><b>File</b</td>
<td><b>Description</b></td>
</tr>
<tr>
<td>models/base_model.py</td>
<td>It defines all common attributes/methods for other classes.</td>	
</tr>
<tr>
<td>models/engine/file_storage.py</td>
<td>Serializes instances to a JSON file and deserializes JSON file to instances.</td>
</tr>
<tr>
<td>console.py</td>
<td>Contains the entry point of the command interpreter.</td>
</tr>
<tr>
<td>models/user.py</td>
<td>It defines subclass User.</td>	
</tr>
<tr>
<td>models/state.py</td>
<td>It defines subclass State.</td>	
</tr>
<tr>
<td>models/city.py</td>
<td>it defines subclass City.</td>	
</tr>	
<tr>
<td>models/amenity.py</td>
<td>It defines subclass Amenity</td>	
</tr>
<tr>
<td>models/place.py</td>
<td>Place file that contains detailed information about the place to be rented.</td>	
</tr>	
<tr>
<td>models/review.py</td>
<td>It defines subclass Review.</td>	
</tr>	
<tr>
<td>tests/test_console.py</td>
<td>unittests for console.</td>	
</tr>	
<tr>
<td>tests/test_models/test_base_model.py</td>
<td>unittests for base_model.</td>	
</tr>	
<tr>
<td>tests/test_models/test_user.py</td>
<td>Unittests for user</td>	
</tr>	
<tr>
<td>tests/test_models/test_state.py</td>
<td>Unittests for state.</td>	
</tr>	
<tr>
<td>tests/test_models/test_city.py</td>
<td>Unittests for city.</td>	
</tr>	
<tr>
<td>tests/test_models/test_amenity.py</td>
<td>Unittests for amenity.</td>	
</tr>	
<tr>
<td>tests/test_models/test_place.py</td>
<td>Unittests for place.</td>	
</tr>	
<tr>
<td>tests/test_models/test_review.py</td>
<td>Unittests for review.</td>	
</tr>
<tr>
<td>tests/test_models/test_engine/test_file_storage.py</td>
<td>Unittests for file_storage.</td>	
</tr>		
</table>
	
	
<b>Tests</b>	

All the code is tested with the unittest module. The test for the classes are inthetest_models folder and All tests should also pass in non-interactive mode:<ul> $ echo "python3 -m unittest discover tests" | bash</ul>
	
<ul>All your tests should be executed by using this command: python3 -m unittest discover tests</ul>

<ul>Test files by using this command: python3 -m unittest tests/test_models/test_base_model.py</ul>
	


	
<b>Author</b> 
	
Kagontle Booysen
	
	

	





