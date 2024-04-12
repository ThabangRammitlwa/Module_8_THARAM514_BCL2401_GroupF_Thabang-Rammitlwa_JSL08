# [JSL08] Submission: Singleton Pattern for Bank Branch Management

BankBranch Singleton Pattern
This JavaScript code implements the Singleton Pattern for managing a single instance of the BankBranch class throughout the application. The Singleton Pattern ensures that there is only one instance of a class, providing a global point of access to that instance.

## overall learning

**Singleton Pattern:** This pattern ensures that a class has only one instance and provides a global point of access to that instance. In the `BankBranch`class, the `bankBranchInstance `variable ensures that only one instance of the class exists throughout the application.
**Class Definition** The `BankBranch` class is defined to manage branch information. It has a constructor to initialize branch information and methods to retrieve this information.
**Constructor Logic:** The constructor checks if the `bankBranchInstance` variable is null. If it is, a new instance is created with the provided branch information. Otherwise, the existing instance is returned. This ensures that there is only one instance of the class.