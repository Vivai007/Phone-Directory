# Phone-Directory
#This program creates a PhoneDirectory class which has a main method. The main method starts by initializing an empty list of Contact objects. It then enters a loop where the user is prompted for a command. If the user inputs "add", the program requests the details for a new contact and creates a Contact object using this information. The newly created Contact object is then added to the list. If the user inputs "search", the program asks for a search query and looks through the list of contacts for any matches. It checks if any of the fields of the Contact object contains the query string. If the user inputs "exit", the program stops running.

The Contact class is used to represent a single contact, with fields for their first name, last name, phone number, and birth date. It also has a method called "matchesQuery" which returns true if any of the contact's fields contain the given query string. Additionally, the class overrides the "toString" method to provide a string representation of the contact's information.#
