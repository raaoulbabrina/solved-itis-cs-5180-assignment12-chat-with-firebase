Download Link: https://assignmentchef.com/product/solved-itis-cs-5180-assignment12-chat-with-firebase
<br>
In this assignment you will get familiar with using with Firebase to manage authentication and data storage.

<h1>Part A: Login</h1>

This is the launcher screen of you app. The wireframe is shown in Figure 1(a). The requirements are as follows:

<ol>

 <li>The user should provide their email and password. The provided credentials should be used to authenticate the user using Firebase Authentication. Clicking the “Login” button should submit the login information to the Firebase Authentication API to verify the user’s credentials.

  <ol>

   <li>If the user is successfully logged in then start the Chat Screen, and finish the Login Screen.</li>

   <li>If the user is not successfully logged in, then show a toast message indicating that the login was not successful.</li>

  </ol></li>

 <li>Clicking the “Sign Up” button should start the Signup Screen Figure 1(b), and finish the login Screen.</li>

</ol>

<h1>Part B: SignUp</h1>

Create the Signup screen to match Figure 1(b), with the following requirements:

<ol>

 <li>Clicking the “Cancel” button should finish the Signup Screen and start the Login Screen.</li>

 <li>The user should provide their first name, last name, email, password and password confirmation. Preform the required validation(the given password and the repeated password must match). Clicking the “Sign Up” button should submit the user’s information to Firebase Authentication API.

  <ol>

   <li>If the signup is not successful display an error message indicating the error message received from the Firebase Authentication API.</li>

   <li>If the signup is successful, then start the Chat Screen and finish the Signup Screen.</li>

  </ol></li>

</ol>

<h1>Part C: Message Threads</h1>

This is the home screen which displays the list of threads as shown in Figures1(c-e) to. Please follow the instructions below:

<ol>

 <li>The top of the screen should display the name of the currently logged in user. The logout button is located in beside the display name.

  <ul>

   <li>Clicking on the ‘logout’ icon should log out the user, finish the the screen, and open the login screen.</li>

  </ul></li>

 <li>The list should display the list of message threads. Which should be retrieved from Firebase.

  <ul>

   <li>Clicking on a thread item should open the Chatroom screen of that thread.</li>

  </ul></li>

 <li>The EditText at the bottom of the screen should enable the user to create a new thread.

  <ul>

   <li>After entering the new thread message, the user clicks the add button, which should send the new thread information to be added to Firebase.</li>

   <li>After a successful addition of a new thread, the list should be updated to show the updated thread list.</li>

  </ul></li>

 <li>The user should be allowed to delete threads that they have created.

  <ul>

   <li>Display a remove icon beside the title of the threads that were created by the current user. Note: the thread information includes the user_id of the user that created the thread.</li>

   <li>Clicking the remove icon should delete the thread by removing the thread from Firebase. Then the list should be updated to display the updated list of threads.</li>

  </ul></li>

</ol>

<h1>Part D: Chatroom (</h1>

This activity displays the list of messages in the particular thread. Also this screen allows the user to add new text messages. The requirements are as follows:

<ol>

 <li>The top of the screen should display the name of the thread as shown in Figure 1(f). Beside the name of the thread there is a home icon button, when clicked should close this activity and display the Message Threads screen.</li>

 <li>For each message display the full name of the user that created the message, the message text, and the time the message was created using the Prettytime Library.

  <ul>

   <li>Display the delete icon only for messages that were posted by the currently logged in user.</li>

  </ul></li>

 <li>The EditText at the bottom of the screen should enable the user to create a new message.

  <ul>

   <li>After entering the new message, the user clicks the add button, which should send the new thread information to the add new message to the current thread on Firebase.</li>

   <li>After a successful addition of a new message, the list should be updated to show the updated message list.</li>

  </ul></li>

 <li>The user should be allowed to delete messages that they have created.

  <ul>

   <li>Clicking the remove icon should delete the message by removing the message from Firebase. Then the list should be updated to display the updated list of message.</li>

  </ul></li>

</ol>