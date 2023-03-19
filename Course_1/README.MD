Crash Course on Python from Google

* Code Reuse
  *defines a generic Animal class
  *define a Turtle class that inherits from the Animal class. Then go ahead and set its category. 
   For instance, a turtle is generally considered a reptile. Although modern cladistics call this 
   categorization into question, for purposes of this exercise we will say turtles are reptiles!
  *This one will require a second type of Animal that is in the same category as the first. 
   For example, since you already created a Turtle class, go ahead and create a Snake class. 
   Don’t forget that it also inherits from the Animal class and that its category should be set to reptile.
  *Fill in the blanks of the Zoo class below so that you can use zoo.add_animal( ) to add instances of the
   Animal subclasses you created above. Once you’ve added them all, you should be able to use zoo.total_of_category( )
   to tell you exactly how many individual Animal types the Zoo has for each category!
   
* Object-oriented programming
In this exercise, we'll create a few classes to simulate a server that's taking 
connections from the outside and then a load balancer that ensures that there are
enough servers to serve those connections.
To represent the servers that are taking care of the connections, we'll use a Server
class. Each connection is represented by an id, that could, for example, be the IP 
address of the computer connecting to the server. For our simulation, each connection
creates a random amount of load in the server, between 1 and 10.

* Practice Notebook - Putting It All Together

* Final Project - Word Cloud 
For this project, you'll create a "word cloud" from a text by writing a script. 
This script needs to process the text, remove punctuation, ignore case and words 
that do not contain all alphabets, count the frequencies, and ignore uninteresting 
or irrelevant words. A dictionary is the output of the calculate_frequencies function. 
The wordcloud module will then generate the image from your dictionary.

Find more:
https://www.coursera.org/learn/python-crash-course/
