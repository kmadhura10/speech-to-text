# speech-to-text
Voice recognition using  machine learning  framework tensor flow 
we can buit deep neural network to recognize  spoken numbers.
1.	 We use a labled data set of people saying numbers.

2.	Then building nural network .
Tflearn is a library featured for higher level API for tensorflow which is easier to read and prototyping .
Speech_data is the second library used to fetch data from the web and helps to  format it
  
3.	Train the machine	
Now we will train by building  our own neural network.
we will use recurrent neural network.
Next level is to use tflearn’s  lstm   long short term memory function 
In this record net, output data content is influenced, not only by the input we just put in but the entire history of out recording loop.

At end, We will use regression, so it will give output as a single predicted number.
See Demo.py for code details.
