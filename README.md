# CodingAssignment

Project is placed in DataProcessor zip file, kindly download and unzip the same to view the project.

Business rules and logic is stored in business folder of the project
	Sub folder of contract and implementation are created to make the code loosely coupled
	For example process contracts only gives contract method to process data, depending on the data type chosen we can have implementation from implementation classes of     various data types
	Any new data type that needs to added in future can simply have its implementation class and give its own implementation of process data.
	Similarly source has its own contract and implementation,any new source can be added easily by adding a new implementation for new source.
	
Factory folder consists of factory classes for source and process, these factory class can on real time provide implementation class for these interfaces.

PS: delegates could also be used to make real time process data definition depending on data type, however interface makes it more loosely coupled and easily manageable.
