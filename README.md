This app was created to prototype a digitalization of a paper process performed at HCA hospitals.  When a surgery has been scheduled, a picklist is created of the supplies a specific doctor requires to perform the surgery, then the items are picked from the warehouse and the amount of each is written on a form.  The form is passed to nurses who take the supplies to the Operating Room, then a clerical tech keeps track of the supplies that are actually used in the surgery.  This record is copied multiple times and used by different employees to bill the patient, make a record of implants put in the patient, and a record of the surgery itself.  All of this is done one paper and passed from person to person, leaving lots of room for error, especially considering the chances of misreading handwriting.

This app seeks to streamline this process, currently with three different user types, scheduler, supply chain management, and clerical tech.

• the scheduler user can schedule surgery, add new patients and users, and add and remove items from a doctor's preference card

• the supply chain user can see a list of picklists for upcoming surgeries and when they choose a picklist, they are presented with the list of items, with a button for each to indicate that the item has been picked, when an affordance to finish the picklist is clicked, the list is hidden from the supply chain user and made available to the clerical tech

• the clerical tech user can see a list of upcoming surgeries and can select a specific one, when they select one they are presented with a list of items collected for that surgery and can indicate the number of each item that is actually used in that surgery

![image](https://user-images.githubusercontent.com/55998907/72085020-2e500480-32ca-11ea-80ac-73349c2f160c.png)

To run this app:

1. Clone down repo

2. make copy of database.json.example, change to database.json

3. npm install in terminal

4. start json-server

5. npm start
