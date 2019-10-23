# Firebase Reserach Questons

What is firebase? 
Firebase is a platform that offers Realtime Databases, File Storage, Authentication, Hosting, and more. 

What is a real time database?
A real time database does not have to make a bunch of HTTP request instead it uses WebSockets as all of your data is sync automatically.

How do you add firebase to you project?
You can use the firebase console, register your app to it, and import in a configuration file.

Where is the meta data(app id, project id) about your firebase project stored in the app?
It is stored in the firebase cloud.

How do you change rules in firebase to read/write to the database?
Though the firebase console in the rule tab in the Database page of the console.

How is the data formatted in firebase?
Data is formatted in JSON.

How do you save a value to the database?
You use a DataReference object which allows the writing or reading data to a firebase database as it represent a location within said database.

How do you save an object to the database?
Same way you store a value you use the the DataReference object and setValue method.

What happens if you set a new value to the save FirebaseReference?
It overwrite the data including any child nodes.

How can you autocreate a key for pushing objects/values to the reference in firebase?
You use DatabaseReference objects push method to create a reference to auto-generated child location

How can you add a child to a firebase reference?
You add a child by using the child method form the DatabaseReference class

How to add authentication to firebase?
You must add implementation 'com.google.firebase:firebase-auth:19.1.0' to your file and check the auth state, sign up new user, and sign in existing users

How to enable a user to create an account using Firebase authentication?

Do you need to enable for other social media sign in as well in the console?
Yes.
