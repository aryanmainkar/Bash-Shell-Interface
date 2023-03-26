# Simple-Command-Line-GUI

# MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<h2 style = "font-size : 18px";>Overview</h2><ul><li>
 This project is a simple implementation of a shell program, called "msh", written in C. The shell is capable of executing basic commands such as cd, ls, cp, script, and exit. It also allows users to define their own shell scripts by executing a file containing a sequence of commands. The project includes a makefile for easy compilation and an automated script for testing the basic functionalities of the shell.</ul></li>
 
 <h2 style = "font-size : 18px";>Getting Started</h2><ul><li>To use the shell, first compile the code using the provided makefile by running the following command in the terminal:
</li>
  "make"
  <br>This will create an executable file named msh. <br><li>To run the shell, simply execute the following command:</li>
  "./msh"</ul>
  
  <h2 style = "font-size : 18px";>Supported Commands</h2><ul><li>
  The shell supports the following basic commands:</li>
  cd : Change the current working directory<br>
  ls : List the contents of the current directory<br>
  cp : Copy a file from one location to another<br>
  script : Record a shell session to a file<br>
  exit : Exit the shell

</ul>

<h2 style = "font-size:18px";>Scripts</h2><ul><li>The shell also allows users to define their own shell scripts by executing a file containing a sequence of commands. </li>
  <li>An automated script is provided to test the basic functionalities of the shell. The script is written in Expect, a scripting language used for automating interactions with command line applications. The script tests the cd, ls, exit, cp, quit, script, and paths commands of the shell.</li></ul>
  
 <h2 style = "font-size:18px";>Conclusion</h2><ul>This project provides a simple implementation of a shell program written in C, capable of executing basic commands such as cd, ls, cp, script, and exit. It also allows users to define their own shell scripts by executing a file containing a sequence of commands</ul>
  

