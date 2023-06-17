# SiddhantDixitTest

## Part- A (Theory)

1) Internet websites typically consist of two main divisions: front-end and back-end. 

	The front-end is the visible part of the website that users interact with. It includes the design, layout, and user interface elements. Front-end technologies such as HTML, CSS, and JavaScript are used to create the structure, styling, and functionality of the website. For example, when you visit a website and see the text, images, buttons, and forms, you are interacting with the front-end. We can also use modern frameworks like ReactJS,, AngularJS, Vue JS to make frontend of our app. These frameworks have lot's of advantages over the simple website with HTML, JS, CSS.

	On the other hand, the back-end of a website refers to the server-side components that handle data processing and storage. It involves the server, the application logic, and the database. The back-end code is responsible for processing user requests, fetching data from databases, and generating dynamic content. Examples of back-end technologies include programming languages like Python, Java, or PHP, and databases like MySQL or MongoDB. The back-end handles tasks like user authentication, database management, and server communication.

	The front-end and back-end divisions work together to create a functional and interactive website. The front-end presents the information and user interface, while the back-end processes and stores the data, providing the necessary functionality for the website to operate.

2) In HTML (Hypertext Markup Language), tags are used to mark up elements and define their purpose within a web page. Each category of tag serves a specific purpose and has a distinct function. Here are some examples:

	- Structural tags: These tags define the structure of the web page. For instance, the `<header>` tag represents the header section of a page, the `<nav>` tag denotes the navigation menu, and the `<footer>` tag represents the footer section.

	- Text formatting tags: These tags control the appearance and formatting of text. For example, the `<h1>` to `<h6>` tags represent headings of varying sizes, the `<p>` tag is used to define paragraphs, and the `<strong>` tag indicates strong emphasis.

	- Link tags: These tags create links to other web pages or resources. The `<a>` tag is used to define an anchor or hyperlink, and the `href` attribute specifies the URL of the linked page or resource.

	- Image tags: These tags are used to display images on a web page. The `<img>` tag is used to insert an image, and the `src` attribute specifies the image source file.

	- Form tags: These tags are used to create interactive forms on web pages. The `<form>` tag wraps the form elements, and the `<input>` tag is used to create various form fields like text input, checkboxes, or radio buttons.

	Each category of HTML tags plays a crucial role in defining the structure, content, and interactivity of a web page.

3) The Virtual DOM (Document Object Model) is a concept used in web development frameworks like React to improve performance and efficiency. The working procedure of the Virtual DOM involves the following steps:
	
	1. Initial rendering: When a web application is loaded, the Virtual DOM is created as an in-memory representation of the actual DOM. It mirrors the structure of the real DOM but doesn't have any visual representation.

	2. Updating the Virtual DOM: When changes occur in the application's state or user interactions trigger updates, the Virtual DOM is modified instead of directly manipulating the real DOM. This step is efficient because updating the Virtual DOM is faster than re-rendering the entire real DOM.

	3. Diffing: After the Virtual DOM is updated, it performs a process called "diffing" to calculate the minimal number of changes required to synchronize the real DOM with the updated Virtual DOM. It identifies the differences between the previous and current Virtual DOM states.

	4. Reconciliation: Once the differences are identified, the framework applies the necessary changes to the real DOM, updating only the	 affected elements instead of re-rendering the entire page. This helps in optimizing performance and reducing unnecessary reflows and repaints.
	
	By using the Virtual DOM, web frameworks can minimize the direct manipulation of the real DOM, leading to faster updates and a more efficient rendering process.

4) MySQL and NoSQL are two different types of database management systems, each with its own characteristics and use cases. Here are some key differences between them:
	
	1. Data structure: MySQL is a relational database management system (RDBMS), which means it organizes data into structured tables with predefined schemas. NoSQL databases, on the other hand, are non-relational and use various data models like key-value pairs, document-oriented, columnar, or graph databases. They provide flexibility in handling unstructured or rapidly changing data.

	2. Scalability: MySQL traditionally relies on vertical scaling, where you increase the capacity of a single server to handle more data. NoSQL databases are designed for horizontal scaling, allowing you to distribute data across multiple servers and scale horizontally as needed.

	3. Query language: MySQL uses SQL (Structured Query Language) for querying and manipulating data. It provides a rich set of features and powerful querying capabilities for complex operations. NoSQL databases often use different query languages or APIs specific to their data models, such as MongoDB's document query language or Cassandra's CQL (Cassandra Query Language).

	4. ACID compliance: MySQL follows the ACID (Atomicity, Consistency, Isolation, Durability) properties, ensuring data integrity and transactional consistency. NoSQL databases, especially in their early iterations, focused more on scalability and performance rather than strict ACID compliance. However, some NoSQL databases now offer varying degrees of ACID compliance, depending on the specific implementation.

	5. Use cases: MySQL is commonly used for traditional data-intensive applications with structured data requirements, such as e-commerce platforms, content management systems, or banking systems. NoSQL databases excel in handling large volumes of unstructured or semi-structured data and are often used in applications like real-time analytics, social media platforms, or IoT data management.

	These are just a few of the differences between MySQL and NoSQL databases, and the choice between them depends on the specific requirements and characteristics of the application.

5) One popular DBMS (Database Management System) technology is MongoDB, which is a document-oriented NoSQL database. In MongoDB, data is stored as flexible JSON-like documents, allowing for dynamic and schema-less data structures. Here's an explanation of MongoDB in simple terms:
	
	Imagine you have a bookstore, and you want to store information about your books. In a traditional relational database, you would define a schema with fixed columns for attributes like book title, author, genre, and publication date. However, in MongoDB, you can store book records as JSON-like documents, where each document can have different attributes depending on the book.

	For example, one book document may have fields like "title," "author," and "genre," while another book document may have additional fields like "publisher" or "ISBN." This flexibility allows you to handle varying data structures without changing the entire database schema.

	With MongoDB, you can perform CRUD operations (Create, Read, Update, Delete) on documents, similar to traditional databases. You can store and retrieve books, search for specific attributes, and even perform complex queries using MongoDB's powerful query language.

	MongoDB also provides scalability by allowing you to distribute your data across multiple servers, handle large amounts of data, and support high-traffic applications.
