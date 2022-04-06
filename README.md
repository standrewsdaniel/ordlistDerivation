
# Specifications from assignment

Project #2	 	Derivation of an OrdList from ABC List Class

(NOTE – when working on this project, do NOT clean the solution.  If you do, there is a good chance the ABCListClass.obj file will be erased, and will need to be redownloaded.)

For this assignment, we will take a much more comprehensive version of the list class discussed in class and use it as a basis for further derivation of another class.

The list class has been modified so that it is an abstract base class, you will take this class and derive an ordered list class (ascending order - no duplicates allowed) from it. 

Additionally, we will not only be extending the class from a regular List Class to an OrdListClass, but we will also be setting it up so that it expands and contracts using a dynamic array instead of a static array.  This expansion and contraction should be internal to the class and hidden from the client as the client should not know or care how the class is manipulated internally only that they know how to use the class. Therefore the class will be considered an ADT and we should enforce all principles of such as Information Hiding and Encapsulation.

Furthermore to show you just how far we can take the encapsulation and information hiding principle, we will not have access to the base classes .cpp file. I will precompile the ABClass into an .obj and we will insert that into our project and use that within our derivation rather than using the ABC List.cpp file.   So you obviously really have NO CLUE as to how I've implemented the methods for the class.

Your first task is to ensure that the ABC list class functions correctly (hint – it does not).  You should utilize the ABCListClass project to test the class thoroughly, and determine what method(s) are broken (that project has a version of the ABCListClass with the PVMs turned off).  You should include a writeup with your final submission as to what is broken and what it does incorrectly (you won't know how the code is broken, but you should be able to describe what does not work correctly).  This part should be submitted to the Project 2 Part 1 dropbox by March 22nd.  The two most important deliverables are your fully documented detailed test client and written writeup.



(continued) 
Once you have identified the error(s) I would suggest that you get the inheritance/overloading of methods within the OrdListClass working without worrying about the expansion and contraction of the list and then add that after you are sure the class works with four elements. It will not cause you to do unnecessary work as good structured modular code can be modified very easily. You should address and test each method independently.

Included in the code you will find the fully documented specification file for the Abstract Base ListClass. You will need to be sure as to how this class is used before you use it as a basis for further derivation of OrdListClass.  (In order to ensure compilation, during this testing phase pure virtual methods are commented out, or modified to no longer be PVMs).  Most of the listed protected methods will be inherited from ABCListClass.  You will use these to access and update the PDM’s of the base class if needed.  If you wish to create additional helper methods for the OrdListClass that is OK, but you should not create any new PDMs without permission.
