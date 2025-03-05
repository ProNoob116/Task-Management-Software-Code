‭Application Features Overview‬

‭1.‬‭ Login Page/Logout‬‭ :‬
○‬‭ The application opens with a login page where the user logs in with their‬ username.‬
○‬‭ If their user doesn’t exist, they must register with a username (minimum 4‭ lowercase letters) and a password (minimum 8 characters with a mix of‬ uppercase, lowercase, symbols, and numbers).‬
○ The user is stored in users.txt and their password is encrypted with the hash‬
○ The "Show Password" option is available by clicking the eye icon.‬
○‬‭ Users can change their username by providing a new username that is not‬ already taken. The system will deny the change if the user is already registered.‬
○‬‭ With the “Remember Me” button, the GUI remembers the username after closing‬‭ the software if the user logs in and then logs out with the button pressed before‬ closing the application.‬
○‬‭ Click the "Logout" button to return to the login page.‬
○‬‭ The “Delete User” button ensures to remove the user and their data from the‬ database.‬
‭
2.‬‭ Task Management‬‭ :‬
○‬‭ Users can add tasks with a due date, category, and priority level.‬
○‬‭ Tasks can be sorted by date, category, or priority using the sort dropdown or by‬ clicking on the column headers.‬
○‭ The GUI supports mouse scrolling to select tasks for easier deletion of multiple‬ tasks.‬
○‬‭ Completed tasks can be deleted and retrieved if needed using the “Undo Task” button or Ctrl + Z.‬
‭
3.‬‭ Category Management‬‭ :‬
○‬‭ Categories can be added manually or are automatically populated based on‬ tasks.‬
○ Existing categories are auto-suggested when entering a new task.‬
○‬‭ Categories are saved in a username_categories.txt file and removed when tasks‬ associated with them are deleted.‬
‭
4.‬‭ Archiving and Restoring Tasks‬‭ :
○ Tasks can be archived (deleted), and the last deleted task can be restored using‬ the “Undo Task” button or Ctrl + Z.‬
○‬‭ Archived tasks are stored in a username_archive.txt file, which is deleted upon‬ logout.‬
‭
5.‬‭ Data Persistence‬‭ :‬
○ Tasks and categories are automatically saved to files named after the user.‬
○‬ These files are loaded upon login to restore the user's previous session.‬
○‬‭ Deleted tasks cannot be retrieved after logging out, ensuring data privacy.‬
○ The user’s data is permanently erased from the database when they delete their‬ account. This includes user info, saved/deleted tasks and their categories.‬
