Download Link: https://assignmentchef.com/product/solved-library-service
<br>
<p class="ui header product-top-header" title="library loaning service Solution">Each operation has a member, and each operation has a Borrowable (Item to be borrowed). Therefore, it’s composition from both sides.

Date is composition with Operation, as each operation has a date.

Library is also composition with Operation, Member and Borrowable. As Library has Operation, Member and Borrowable (Item to be borrowed).

Inheritance only between (Students, Employee, Faculty) and Member. As Students, Employee, Facultyinherit  from Member.Library System:

We assume this system is going to be used by a librarian person at the library to facilitate library loaning service offered to university community. The system should track books and periodicals and their borrowing operation. The policy of items borrowing is illustrated by the following table:

The following class diagram displays the model of this system

Notes:

– You should have a class Date to represents date of borrow operation.

– You need one more class in this mode call it Library that has array list of Members, array list of Borrowable , and array list of Operation.

– Your system should provide the following functionalities:

1- Add member:

– Student

– Employee

– Faculty

2- Add item:

– Book

– Periodical

(When new item is added, its status is true i.e. considered available

3-     Borrow an item.

When the librarian enters member’s id, his name is displayed, then ISBN or ISSN is entered then title of the item is displayed. The system should apply the library policy above, so if the user reaches maximum allowed of items, system should display a dialog message indicating this restriction, and should not allow this operation. Moreover, system ensures the availability of the item (its status is true). If the operation is correct, your system should change the status of that item to false, and create an object of Operation (its type is “Borrow”) and add it to the array list of Operation.

4-     Return an item.

When librarian enters ISBN or ISSN of the item, it displays its title, and member name who borrowed that item then when he pressed “Return” button, the item’s status is changed to true, it also create an object of Operation (its type is “Return”) and add it to the array list of Operation.

5-     Search.

Search for item by title.

6-     Reports.

–         Items are currently borrowed by a member: where librarian enters member’s id, then the system display titles of all items that are currently borrowed by that member (not return yet).

–         Borrowed by a specific date: where librarian enters the date, the system should display all items titles, type, and name of member for items that were borrowed on that specific date.

7-     Save data to the disk.

8-     When system starts, it should upload previous date (if there is).

<span class="kksr-muted">Rate this product</span>

<span class="likes"> </span>