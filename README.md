# BookSharing

## Database
<p align="center">
  <img src="stuff/database.jpg" alt="Database">
</p>

## Auth
void login (string email, string password) <br>
void register (string email, string password) <br>
void delete_account () <br>
void logout () <br>
void change_password (string password) <br>

## Interfaces
void addBook (<all of the book properties (books table in database)>) <br>
void modifyBook (<all of the book properties>) <br>
void deleteBook (int book_id) <br>
List\<book> searchByTitle (string title) <br>
List\<book> searchByUser (int user_id) <br>
List\<book> searchByAuthor (string author) <br>
(all searches will probably be done in one method, to every one also boolean only_available could be added)  <br>
void borrowBook (int book_id, int new_holder_user_id) <br>
void returnBookToOwner (int book_id) <br>

## Android Classes
1. ViewClasses -> back-end classes for every view in application to handle events like clicking button, etc. <br>
2. HttpsService -> Class that handles https requests and responses <br>
3. HttpsRequests -> Class with requests to DB server, GET's, POST's <br>
4. HttpsAuthorisation -> Also requests to server, but different class to separate security stuff <br>
5. BookEntity -> Java class that is representation of Book in DB <br>

## Database Classes
1. BookRepository
2. BookController
3. BookEntity
4. AuthRepository
5. AuthController
6. UserEntity

## iPhone
TBD