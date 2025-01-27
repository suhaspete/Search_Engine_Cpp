# Search_Engine_Cpp

A C++ Search Engine operates through List type collection features alongside Map functions with Trie field structures.

A C++ search engine project includes List and Map and Trie data structures for performing keyword searches on text documents. The project shows how lists combined with maps together with tries can search through large datasets to find specific keywords effectively.

## Getting Started

Users need to download the project's source files then build the code on their system's local environment before starting this project. An executable binary will form after compilation which you can run through a terminal input of a text file. The make file allows code execution through terminal.

## Prerequisites

Programming this application requires that your system contains a C++ compiler installed. Our recommendation for compiler selection includes g++ for Linux users and Microsoft Visual Studio for Windows operating systems.

### Compiling the Program

1. Users can retrieve the source code from the Github repository.


2. Access your directory's terminal application making sure you are in the same location as where you saved the downloaded source code files.


3. Compile the program using the following command:
      
        g++ -std=c++11 searchengine.cpp -o search_engine

We can find the newly created executable search_engine positioned alongside the same directory folder.     

## Running the Program

1. Use a terminal window to reach the directory which contains your compiled program.

2. Run the program by providing the name of the text file you want to search as a command-line argument:

        ./search input.txt     
   The name of your selected file must be entered as a replacement for input.txt during execution.


Enter a keyword when the program asks after starting its execution. Use the keyword then tap the Enter key.

The program will conduct a keyword search through the selected text file to show its results.
s in alphabetical order.

- to compile it
make
to run it pass to the same folder a txt file with the correct format such as(smalldataset and bigdataset) or give relative path or full path
./searchengine -d smalldataset.txt -k 5


