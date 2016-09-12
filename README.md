# osticket_custom_column
Display data from form in a custom column

Steps taken.

First in OS Ticket goto Manage > Forms

To add a Company item that the user fills in when submitting a ticket go into Contact Information, add a required custom list item called 'Company Name' and save the modification.

When a new ticket is created the user submitting it will now be required to enter a Company Name.

Next backup the tickets.inc.php file found in the include/staff folder of your osTicket installation then replace the current version with the new tickets.inc.php file. Make changes outlined in tickets.inc.php file.
