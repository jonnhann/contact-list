import java.io.Serializable;
import java.util.ArrayList;
import java.util.Scanner;
import java.util.Collections; 
import java.util.Comparator; 


/*
 * One object of Class ContactList represents the contact list.
 * This class performs following functions:
 * 1. User adds their information information into the contact list
 * 2. Prints the contact list
 * 3. Retrieves person's info by last name
 * 4. Quits the program and saves to disk
 * 5. Open the existing data file onto the disk.
 */
public class ContactList implements Serializable {
	private ArrayList<Contact> contactList = new ArrayList<Contact>();
	
	public ContactList(){
	
	}
	
	/*This will be used for Use Case 1:
	 * User enters information.
	 * Verifies that last name is filled.
	 */
	public void addContact(){
		
	}
	/*This will be used for Use case 2:
	 * Prints contact list.
	 * Sorts by last name.
	 */
	public void printList(){
		
	}
	/*This will be used for Use case 3:
	 * Retrieves information by last name.
	 */
	public void searchByLastName(){
		
	}
	/*This will be used for Use case 4:
	 * Quits the program and saves to disk
	 */
	public void quitAndSave(){
		
	}
	/*This will be used for Use case 5:
	 * Starts up program and opens existing data file
	 */
	public void openFile(){
		
	}
	
	
	
	
	
}
