# JSON Exercices
This repository provides various types of exercices, all focused on **JSON**.

> **EXERCICE 1**

Given the following graphic, used in the previous unit,
constructs the corresponding JSON document.
Assign the types of data you consider appropriate,
apart from those indicated.
Also add a boolean type data, in the cycle objects,
called “morning”, which will indicate whether the cycle
is taught in the morning or not (the only cycle that will
be taught in the afternoon will be the "NISA" cycle).
In the next slide you can see the scheme:

![Captura de pantalla 2024-06-20 185904](https://github.com/JavierCornejoLeal/EjerciciosJSON/assets/172435006/ffdd88d7-b150-4e74-8d43-9bd0ef6d645e)

> **EXERCICE 2**

Design a JSON that represents the data of two
fictitious user.
The JSON must include the following information:<br>
• Full name of the user.<br>
• User's age.<br>
• User's email address.<br>
• User's address, which should include street,number, city, and country.<br>
• User's list of interests.<br>
• User's activity status (active/inactive).<br>

> **EXERCICE 3**

Create a JSON file containing information about
different books.
Each object in the JSON must represent a book
and include the following details: book title,
author, availability in stock (may or may not be
available) and the literary styles associated with
the book (include at least 2 styles for each book).
Be sure to include at least two books with their
respective details.

> **EXERCICE 4**

As part of a task, you are asked to modify a JSON file
containing information about different products in an
online store catalog.
Each object in the JSON represents a product and
includes the following details: the product ID, the
name, the price and a boolean indicating whether the
product is on sale or not.
In addition, an additional object called "specifications"
must be included that contains product-specific details
such as brand, color, and other relevant specifications.

The information of the products to be added is specified below:

![Captura de pantalla 2024-06-20 185811](https://github.com/JavierCornejoLeal/EjerciciosJSON/assets/172435006/4ef6fd33-3b9e-4d3d-a125-2d1cce506c5a)


> #### EXERCICE 5 <br>

**Objective:**<br>
The objective of this activity is to show how to
convert a JSON string into JavaScript objects and
then access the information contained in them for
display in an HTML document.<br>
**Description:**<br>
Create an HTML document containing a JSON
string with the information from two books (the
ones created in exercise 1).
The JSON string is converted into JavaScript
objects using the JSON.parse() method.
Subsequently, the information for each book is
accessed and displayed in the HTML document.<br>
**Steps to follow:**<br>
• JSON string: A JSON string containing the information of
two books, including the title, author, stock availability,
and literary styles, is provided.<br>
• JSON parse: Using the JSON.parse() method, the JSON
string is converted into JavaScript objects.<br>
• Access to information: information about each book is accessed,
including title, author, in-stock availability, and literary styles.<br>
• Display information: The information for each book is displayed in
the HTML document using HTML elements such as headers and paragraphs.<br>
**Additional details:**<br>
Each book is displayed in a separate section, with
its corresponding information.
The innerHTML property is used to assign each
book's information to the corresponding HTML
elements in the document.
A combination of JavaScript and HTML is used to
achieve dynamic display of the information in the
web browser.

![Captura de pantalla 2024-06-20 191223](https://github.com/JavierCornejoLeal/EjerciciosJSON/assets/172435006/ea7232a5-d607-4cd4-a5ab-faf2fac704be)

> **EXERCICE 6** <br>

**Objective:**<br>
The objective of this activity is to display product
information stored in a JSON format in an HTML
document using the JSON.stringify() method. <br>
**Description:**<br>
Using the data obtained in exercise 3, insert this
JSON data into the HTML document. The goal is
to display this information in an HTML document
in a readable and organized manner.
**Steps to follow:** <br>
• JSON Data: A dataset is provided in JSON format containing the
information of several products, including their name, price,
availability on offer, and specifications.<br>
• Parse and Display: Using JavaScript, the JSON is parsed and the
information for each product is accessed. Then, using the
JSON.stringify() method, the information is converted into
readable strings that are displayed in the HTML document.<br>
• HTML organization: You organize the product information in the
HTML document in a readable and structured way. Each product is
displayed in a separate section with a header indicating the
product number.<br>
• Visual Presentation: HTML elements such as headers and
paragraphs are used to present the information for each
product. Attention is paid to the readability and visual organization
of the information.
 
![Captura de pantalla 2024-06-20 191223](https://github.com/JavierCornejoLeal/EjerciciosJSON/assets/172435006/9a9961a4-2e5a-43cf-a332-21ba4ce2a6fe)

