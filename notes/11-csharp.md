# c-sharp

dotnet cli -> used to create projects

Be sure to specify the type
ex int = 5
string greeting = "hello "
char h = 'h'
bool cool = true
decimal d = 6.8m
double y = 5.5
float f = 5.7

Dictionary<int, string> weird = new Dictionary<in, string>()

// Arrays are immutable in csharp
int[] numbers = { 2,3, 4, 5 }

// Alternative to array to allow editing

List<int> list = new List<int>(){ 1, 2 }

We'll utilize dictionary for objects

We'll utilize list in sharp for arrays

We'll use class when using different types

/Creating a class

we can define if the fields are public or private for the
fields below.

class Cat
{
public string name;
public int age;
public string color;

}

public Cat(string name, int age, string color)
{
this.name = name;
this.age = age
this.color = color;
}

List<Cat> catHotel = new List<Cat>();

catHotel.Add(new Cat("Maxell",2, "yellow-green"))

allows us to input values into the console to read.
Console.ReadLine()

==========
Folder directory overview
Main houses the root file (entry )

dotnetrestore will redownload all projects packages.

Appsetting location -> location for db connection and Auth0

wwwRoot locaiton to house index (web files)

Repositories pulls in the data from the DB

# creating a csharp flow

Need to create controller and correlating service
Then create Model

well need to create a Repository

decorators specify the api controller , and route

(postman) -> ssl may need to be turned off

In startup we'll need to add versions / instances to inject our class/services
example -> importing cats service / repository

NOTE remember to build the application to verify

======= Continued Wed 1/18

CASCADE (built in function) in the the dbsetup to help remove any related data

Task is a return type in the controller we can use to specify async ops

FindAll same as filter in javascript

Using the Authorize decotor requires the use of authProvider(ie have to be logged in for request.o)
