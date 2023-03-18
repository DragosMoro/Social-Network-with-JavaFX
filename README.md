<body>
	<h1>Social Network App in Java with JavaFX GUI</h1>
	<p>This is a social network app developed in Java with a GUI implemented using JavaFX. The app allows users to register and login to their account, add or remove friends, delete their account, view their friend list and user list, accept or reject friend requests, cancel pending friend requests and send messages to their friends.</p>
 <h2>Features</h2>
<ul>
	<li><strong>Login/Register:</strong> Users can create an account by registering with their email and a strong password. Once registered, they can login to their account by providing their email and password.</li>
	<li><strong>Add/Remove Friend:</strong> Users can add or remove friends by searching for their email address or username. They can also view their friend list and the list of users on the app.</li>
	<li><strong>Delete Account:</strong> Users can delete their account at any time.</li>
	<li><strong>Accept/Reject/Cancel Friend Request:</strong> Users can accept or reject friend requests from other users. They can also cancel pending friend requests sent to other users.</li>
	<li><strong>Send Messages:</strong> Users can send messages to their friends.</li>
</ul>

<h2>Screenshots</h2>
<h3>Login Screen</h3>
<img width='300px' src="/screenshots/Screenshot 2023-03-18 150255.png" alt="Login Screen">

<h3>Registration Screen</h3>
<img width='300px' src="/screenshots/Screenshot 2023-03-18 150354.png" alt="Registration Screen">

<h3>Main Screen</h3>
<img width='500px' src="/screenshots/Screenshot 2023-03-18 151602.png" alt="Main Screen">

<h3>Send Message Screen</h3>
<img width='300px' src="/screenshots/Screenshot 2023-03-18 151617.png" alt="Send Message Screen">

<h2>Non-Functional Features, Technologies, and Patterns Used</h2>
<p>The following are the non-functional features, technologies, and patterns used in the app:</p>
<ul>
<li><strong>Database Persistence (PostgreSQL):</strong> The app uses a PostgreSQL database for persistence. PostgreSQL is a powerful, open-source object-relational database system that is widely used in the industry.</li>
	<li><strong>Layered Architecture:</strong> The app is built using a layered architecture pattern, which separates the presentation layer (GUI), application logic layer (controllers), and data access layer (DAOs) into separate components. This makes the app more modular, scalable, and easier to maintain.</li>
 <li><strong>Generics:</strong>Generics were used in various parts of the app to enable the creation of reusable code that can work with different types of objects, making the app more flexible and extensible. The use of generics also follows the OOP principle of abstraction, which separates the implementation details of a class from its behavior, making the code more modular and easier to maintain.</li>
 <li><strong>Observer, Factory, Singleton Patterns:</strong> TThe app uses various design patterns, including Observer, Factory, Singleton, and others, to achieve various functionalities and maintainability. These patterns follow the OOP principles of abstraction, encapsulation, inheritance, and polymorphism, which make the code more organized, reusable, and easier to understand.</li>
</ul>
</body>
