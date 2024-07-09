# PRODIGY_SD_03


Develop a program that allows users to store and manage contact information. The program should provide options to add a new contact by entering their name, phone number, and email address. It should also allow users to view their contact list, edit existing contacts, and delete contacts if needed. The program should store the contacts in memory or in a file for persistent storage.


explanation : Contact List

The program starts by initializing an empty contact list contact_list. This list will store all the contacts added by the user.

Functions

The program defines five functions:

add_contact(): This function adds a new contact to the contact list. It prompts the user to enter the contact's name, phone number, and email address, and then creates a dictionary to store this information. The dictionary is then added to the contact list.
view_contacts(): This function displays the contact list. It iterates over the contact list and prints each contact's information, along with a number for easy reference.
edit_contact(): This function allows the user to edit an existing contact. It first displays the contact list, and then prompts the user to enter the number of the contact they want to edit. It then updates the contact's information based on the user's input.
delete_contact(): This function allows the user to delete a contact. It first displays the contact list, and then prompts the user to enter the number of the contact they want to delete. It then removes the contact from the list.
save_contacts_to_file(): This function saves the contact list to a file named "contacts.txt". It opens the file in write mode, and then writes each contact's information to the file, separated by commas.
load_contacts_from_file(): This function loads the contact list from the "contacts.txt" file. It opens the file in read mode, and then reads each line of the file, splitting it into name, phone number, and email address. It then creates a dictionary for each contact and adds it to the contact list.
