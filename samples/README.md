## let's look at examples


**file:** ``firstNode.js``
> ``console`` _provides simple methods for writing to stdout, stderr, or any other Node.js stream, which is mostly the command line_<br>
> ``process`` _is a global object that contains functions and data related to the current Node.js process;_<br>
> ``argv`` _is an array of strings containing all command-line arguments given to the program;_<br>

> when you run this program, you provide a command line argument like this:<br>
> run ``node firstNode.js hello arguments``<br>
> Output   =>>>   ['C:\\Program Files\\nodejs\\node.exe', 'E:\\IT-KiSe\\school-Node\\firstNode.js', 'hello', ' arguments ' ]
> > + in the [process.argv array]
> >   - 1st argument is the location of the Node.js binary file
> >   - 2nd argument is the location of file that is being launched

> change ``console.log(process.arg);`` to the following ``console.log(process.argv.slice(2));``<br>
> run ``node firstNode.js hello arguments``<br>
> > Output  =>>>   [ 'hello', ' arguments ' ]

> Environment variables are key-value data stored outside the program and provided to the OS.
> > ``env object`` stores all the environment variables that are available when Node.js runs the application

> run the program as follows: 
> > + ``node firstNode.js HOME PWD USER PATH``
> > + ``node firstNode.js HOMEPATH PROCESSOR_IDENTIFIER USERPROFILE``
___

**file:** ``Hello-Node.js``
> ``__dirname`` _is a global variable that stores the folder in which the script file is located_

&emsp; The **web server** receives HTTP requests from clients, including your browser, and sends them HTTP responses, such as HTML pages or JSON code from an API.
> + Client software is responsible for rendering content such as navigation bar colors and text styles.
> + Server software is responsible for the exchange, processing and storage of data.

___



