![HBNB-HolbertonAirbnb (2)](https://user-images.githubusercontent.com/106469425/215296391-1259f85f-161b-4773-bd79-32077f2789f5.png)


<b>0x00.AirBnB Clone - The Console</b>

### 📝 Description
***
__Airbnb__ is an online platform that connects people who have a home to offer, with people who need a place to stay temporarily.

The first stage of the project was where we started to create The AirBnB Clone and we created a shell to manage the AirBnB objects.

This first stage of the project focused on everything related to Python:

`Import`,` Exceptions`, `Class`, `Private attribute`, `Getter / Setter`, `Class method`, `Static method`, `Inheritance`, `Unittest`, `Read / Write file`, `args` and `kwargs`, `Serialization` / `Deserialization` and `JSON`.

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:
* Create simple HTML static pages
* Style guide
* Fake contents
* No Javascript
* No data loaded from anything

__*HTML*__ (HyperText Markup Language)

Provide structure and meaning to content by defining that content, such as headings, paragraphs, or images. Es the structure of your page, it should be the first thing to write.

__*CSS*__ (Cascading Style Sheets)

It is a presentation language created to style the appearance of content, using, for example, fonts or colors. Is the styling of your page, the design.

Phases of the AirBnB clone project:
- [x] **The console**
- [x] **HTML**
- [ ] MySQL
- [ ] Fabric
- [ ] Flask
- [ ] REST API
- [ ] Web dynamic

<b><h3><u>Functionalities of this command interpreter:</u></h3></b>
<ol>
<li>Create a new object (ex: a new User or a new Place)</li>
<li>Retrieve an object from a file, a database etc...</li>
<li>Do operations on objects (count, compute stats, etc...)</li>
<li>Update attributes of an object</li>
<li>Destroy an object</li>
</ol>

<u><b><h3>Requirements</h3> </b></u>
<li>Allowed editors: vi, vim, emacs.</li>
<li>Files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5).</li>
<li>Files must be executable.</li>
<li>The length of your files will be tested using wc</li>
<li>All your test files should be inside a folder tests</li>
<li>You have to use the unittest module.</li>
<li>All your test files should be python files (extension: .py).</li>
<li>All your test files and folders should start by test_.</li>
<li>All your tests should be executed by using this command: python3 -m unittest discover tests.</li>
<li>Code should use the PEP 8 style (version 2.7.*).</li>
<li>Your code should be W3C compliant and validate with W3C-Validator.</li>
<b><h3>Installation</b></h3>
<ol>
<li>Clone this repository: git clone"https://github.com/KagontleBooysen/AirBnB_clone.git"</li>
<li>Access AirBnb directory: cd AirBnB_clone</li>
<li>Run hbnb(interactively): ./console and enter command</li>
<li>Run hbnb(non-interactively): echo "" | ./console.py</li>
</ol>


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
	
	
<b>Testing</b>	

All the code is tested with the unittest module. The test for the classes are inthetest_models folder and All tests should also pass in non-interactive mode:<ul> $ echo "python3 -m unittest discover tests" | bash</ul>
	
<ul>All your tests should be executed by using this command: python3 -m unittest discover tests</ul>

<ul>Test files by using this command: python3 -m unittest tests/test_models/test_base_model.py</ul>
	
```bash
root@c698ec171c6e:/home/AirBnB_clone# ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
(hbnb) 
(hbnb) quit
$
```

##### all
```bash
(hbnb) User.all()
[[User] (246c227a-d5c1-403d-9bc7-6a47bb9f0f68) {'first_name': 'Betty', 'last_name': 'Bar', 'created_at': datetime.datetime(2017, 9, 28, 21, 12, 19, 611352), 'updated_at': datetime.datetime(2017, 9, 28, 21, 12, 19, 611363), 'password': '63a9f0ea7bb98050796b649e85481845', 'email': 'airbnb@mail.com', 'id': '246c227a-d5c1-403d-9bc7-6a47bb9f0f68'}, [User] (38f22813-2753-4d42-b37c-57a17f1e4f88) {'first_name': 'Betty', 'last_name': 'Bar', 'created_at': datetime.datetime(2017, 9, 28, 21, 11, 42, 848279), 'updated_at': datetime.datetime(2017, 9, 28, 21, 11, 42, 848291), 'password': 'b9be11166d72e9e3ae7fd407165e4bd2', 'email': 'airbnb@mail.com', 'id': '38f22813-2753-4d42-b37c-57a17f1e4f88'}]
(hbnb) 
```

##### show
```bash
(hbnb) User.show("246c227a-d5c1-403d-9bc7-6a47bb9f0f68")
[User] (246c227a-d5c1-403d-9bc7-6a47bb9f0f68) {'first_name': 'Betty', 'last_name': 'Bar', 'created_at': datetime.datetime(2017, 9, 28, 21, 12, 19, 611352), 'updated_at': datetime.datetime(2017, 9, 28, 21, 12, 19, 611363), 'password': '63a9f0ea7bb98050796b649e85481845', 'email': 'airbnb@mail.com', 'id': '246c227a-d5c1-403d-9bc7-6a47bb9f0f68'}
(hbnb) User.show("Bar")
** no instance found **
(hbnb) 
```

#### create
```bash
(hbnb) create BaseModel
49faff9a-6318-451f-87b6-910505c55907
(hbnb) all BaseModel
["[BaseModel] (49faff9a-6318-451f-87b6-910505c55907) {'created_at': datetime.datetime(2017, 10, 2, 3, 10, 25, 903293), 'id': '49faff9a-6318-451f-87b6-910505c55907', 'updated_at': datetime.datetime(2017, 10, 2, 3, 10, 25, 903300)}"]
(hbnb)
```

	


	
<b>Author</b> 
	
Kagontle Booysen
	
	

	





