 ### Airbnb Clone

<h1 align ="center">  <img src="https://www.triada.com.pe/noticias/wp-content/uploads/2019/10/triada-airbnb-obtener-ganancias-departamento-nuevo.jpg" height="100%" width="100%"></h1>

 #### Description
 > This is the first phase of the Airbnb Clone: the console.
 > This repository holds a command interpreter and classes (i.e. BaseModel class
 > and several other classes that inherit from it: Amenity, City, State, Place,
 > Review), and a command interpreter. The command interpreter, like a shell,
 > can be activated, take in user input, and perform certain tasks
 > to manipulate the object instances.

 #### How to Use Command Interpreter
 ---
 | Commands  | Sample Usage                                  | Functionality                              |
 | --------- | --------------------------------------------- | ------------------------------------------ |
 | `help`    | `help`                                        | displays all commands available            |
 | `create`  | `create <class>`                              | creates new object (ex. a new User, Place) |
 | `update`  | `User.update('123', {'name' : 'Greg_n_Mel'})` | updates attribute of an object             |
 | `destroy` | `User.destroy('123')`                         | destroys specified object                  |
 | `show`    | `User.show('123')`                            | retrieve an object from a file, a database |
 | `all`     | `User.all()`                                  | display all objects in class               |
 | `count`   | `User.count()`                                | returns count of objects in specified class|
 | `quit`    | `quit`                                        | exits                                      |

 #### Installation
 ```
 git clone git@github.com:IverSutizal/holbertonschool-AirBnB_clone.git
 cd AirBnB_clone
 ```
 #### Usage
 Interactive Mode
 ```
 $ ./console.py
 (hbnb) help

 Documented commands (type help <topic>):
 ========================================
 EOF  help  quit

 (hbnb)
 (hbnb)
 (hbnb) quit
 $
 ```
 Non-Interactive Mode
 ```
 $ echo "help" | ./console.py
 (hbnb)

 Documented commands (type help <topic>):
 ========================================
 EOF  help  quit
 (hbnb)
 $
 $ cat test_help
 help
 $
 $ cat test_help | ./console.py
 (hbnb)

 Documented commands (type help <topic>):
 ========================================
 EOF  help  quit
 (hbnb)
 $
 ```

 ### Environment
 * Language: Python3
 * OS: Ubuntu 20.04 LTS
 * Style guidelines: [PEP 8 (version 1.7)](https://www.python.org/dev/peps/pep-0008/) \|| [Google Style Python Docstrings](http://sphinxcontrib-napoleon.readthedocs.io/en/l\atest/example_google.html) || [WC3 Validator](https://github.com/holbertonschool/W3C-Validator)

 ### Authors
* [<img src="https://avatars.githubusercontent.com/u/105623752?s=96&v=4" width=130><br><sub> Carlos Cantoral</sub>](https://github.com/carloscm2022)

* [<img src="https://avatars.githubusercontent.com/u/104711420?v=4" width=130><br><sub> Iver Sutizal </sub>](https://github.com/IverSutizal)

* [<img src="https://avatars.githubusercontent.com/u/101225802?v=4" width=130><br><sub> Aaron Jauregui </sub>](https://github.com/aaronJau21)
