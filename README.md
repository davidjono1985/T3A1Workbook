
# T3A1 - WORKBOOK
#### By David Johnson

## Question 1 
```
Provide an overview and description of a standard source control process for a large project
```
![Source Control](./docs/version_control.jpg)

Source control = version control
Online repository eg github
Branching
Merging (staging environment)


## Question 2
```
What are the most important aspects of quality software?
```
•	Functional Quality
•	Structural Quality
•	Functional Quality

•	Reliable
•	Understandable
•	Modifiable
•	Usabille
•	Scalable
•	Testable
•	Portable
•	Efficient

## Question 3
```
Outline a standard high level structure for a MERN stack application and explain the components
```

4 components: provide an end-to-end framework for developers to work in
Mongo DB:
Express.js
React
Node.js
 

## Question 4
```
A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?
```
Source control (or version control) is the practice of tracking and managing changes to code. 

A source code management (SCM) system is utilized to streamline the development process and to provide a centralized source for all of the code.

SCM systems allow the tracking of code changes, revision history for the code, and the ability to revert to previous versions of a project when needed. 

By using a SCM system, you can collaborate on code with your team, isolate your work until it is ready, and quickly trouble-shoot issues by identifying who made changes and what the changes were. 

A standard process for managing source control is as follows:
1.	Use a source control system.
2.	Keep your source code in source control 
3.	Ensure the working file is from the latest version of the source file.
4.	Only check-out the file being worked upon.
5.	Check in immediately after alterations are completed.
6.	Review every change before committing. 
7.	Commit often 
8.	Make extensive, detailed notes in the check-in comments about why the changes were made.

## Question 5
```
With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges
```
There is no real standard when it comes to testing. 

The aim of any software testing process is to investigate, analyse and evaluate a piece of software and its features in order to detect the differences between existing and required conditions (defects/bugs/errors).  

![Testing](./docs/Testing.jpg)

There are many different types of testing concepts and practices that can be used to make sure an application is working correctly. A common method is **manual testing** - which falls under a testing type called a functional test.   These types of tests do not check the intermediate states of an action but instead focus on comparing the output to the expectations.   

In order to manually test something, a tester will start with a list of expectations and then personally test the application against that list.  A test passes when the tester gets back what was expected, and fails if it doesn't.  

Fails are recorded in detail, including specifics on how to recreate the failure.  These are then fed back into the development cycle as bugs to be fixed and are usually categorised by severity level – blocker, critical, major minor and cosmetic.

## Question 6
```
With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature
```

Information System Security is necessary in order to prevent unauthorized access, use, disclosure, disruption, modification, inspection, recording or destruction of information – whether in a physical or electronic state.

The three main requirements for information system security are confidentiality, integrity and availability:

**Confidentiality**  refers to protecting information from being accessed by unauthorized parties.  It ensures that the necessary level of secrecy is enforced at each junction of data processing, thus preventing unauthorized disclosure.

**Integrity:**  ensures the accuracy, reliablitiy and authenticity of information.  It provides assurance that the source of the information is genuine and that it has not been altered through unauthorized modification.

**Availability:**  ensures reliability and timely access to data and resources is available to authorized individuals.

## Question 7
```
Explain control flow, using an example from the JavaScript programming language
```
There are many methods used to protect information and data.  The most common are as follows:

**Risk Assessment:** is the process of discovering, correcting and preventing security problems. It involves identifying various information assets that could be affected by a cyber-attack (such as hardware, systems, laptops, customer data etc.). And then identifies the various risks that could affect those assets.

**Access Controls:** This is effectively limiting employee access to sensitive data.  The fewer people who have access, the lesser the risk of data breach or loss.

**Encryption:** Data encryption applies a code to every individual piece of data and will not grant access to encrypted data without an authorized key being given

**Pseudonymisation:** is a technique that encodes personal data with artificial identifiers such as a random alias or code. It’s similar to writers who use pseudonyms to hide their identities.

**Data masking:** Masking specific areas of data to protect it from internal and external malicious sources.  For example, the first 12 digits of a credit card number may be masked within a database.

**Backups (Data resilience):** By creating backup copies, organizations can recover data should it be erased or corrupted accidentally or stolen during a data breach.

**Destruction:**  protects data against unauthorised recovery and access. Hard disks are most often destroyed using degaussing, whereas paper documents, CDs and tape drives are shredded into tiny pieces.  Encrypted data can easily be deleted simply by destroying the decryption keys.

## Question 8
```
Explain type coercion, using examples from the JavaScript programming language
```

Organisations, agencies and business owners are responsible for protecting users' personal information from:
- theft
- misuse
- interference 
- loss
- unauthorised access
- modification
- disclosure

They are also responsible for securing, destroying or de-idenitfying the data when it's no longer required.

This is a legal requirement under the Australian
[Privacy Act 1988.](https://www.legislation.gov.au/Details/C2014C00076 "Privacy Act 1988")

The Privacy Act regulates the way individuals’ personal information is handled and gives individuals greater control over the process.

Under the Act, an individual has the right to: 

- know why their personal information is being collected, how it will be used and who it will be disclosed to

- have the option of not identifying themselves, or use of a pseudonym in certain circumstances

- ask for access to their personal information (including health information)

- stop receiving unwanted direct marketing

- ask for personal information that is incorrect to be corrected

- make a complaint about an organisation or agency the Privacy Act covers, if they think they’ve mishandled your personal information

The [Australian Privacy Principles](https://www.oaic.gov.au/privacy/australian-privacy-principles/australian-privacy-principles-quick-reference/ "APP") have been developed specifically to help organisations understand their obligations under the [Privacy Act](https://www.legislation.gov.au/Details/C2014C00076 "Privacy Act 1988")

![Privacy](./docs/Privacy.png)


```
"The Australian Privacy Principles (or APPs) are the cornerstone of the privacy protection framework in the Privacy Act 1988 (Privacy Act). They apply to any organisation or agency the Privacy Act covers.

There are 13 Australian Privacy Principles and they govern standards, rights and obligations around:

•	the collection, use and disclosure of 
    personal information

•	an organisation or agency’s governance and
    accountability

•	integrity and correction of personal information

•	the rights of individuals to access their   
    personal information

The Australian Privacy Principles are principles-based law. This gives an organisation or agency flexibility to tailor their personal information handling practices to their business models and the diverse needs of individuals. They are also technology neutral, which allows them to adapt to changing technologies.

A breach of an Australian Privacy Principle is an ‘interference with the privacy of an individual’ and can lead to regulatory action and penalties."

REFERENCE: https://www.oaic.gov.au/privacy/australian-privacy-principles
```
## Question 9
```
Explain data types, using examples from the JavaScript programming language
```
A **relational database** is a collection of related data **tables**, each having a unique name. 

**Columns** describe the specific pieces of information in the table and each **row** stores the corresponding data. A row in a table represents a **relationship** among a set of values and therefore, a table represents a collection of relationships.

A **primary key** is one column or compilation of several columns that has a unique value, making each row unique in the table. Every table must have a primary key because it is used to link data in related tables. 

A **foreign key** is the primary key from another table and is used to relate rows of data between tables.

## Question 10
```
Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language
```
Data integrity is the overall completeness, accuracy and consistency of data. It is usually imposed during the database design phase, and ensures that all data can be traced and connected – which makes everything searchable and recoverable. 

Having a single, well-defined and well-controlled data integrity system increases stability, performance, reusability and maintainability.  Three types of integrity constraints are an inherent part of the relational data model: 

**Entity Integrity:** The existence of the Primary Key is the core of Entity Integrity. The rule states that every table must have its own primary key and that each has to be unique and not null. The system enforces Entity Integrity by not allowing operations (INSERT, UPDATE) to produce an invalid primary key. 

**Referential Integrity:** refers to the accuracy and consistency of data within a relationship.  Any column in a base table that is declared a foreign key can only contain either null values or values from a parent table's primary key or a candidate key. This can be enforced in a relational database by requiring a valid, existing existing primary key to be referenced in the parent table every time a foreign key value is used.

**Domain Integrity:** states that all columns in a relational database are in a defined domain. The system enforces Domain integrity by ensuring all data in a field contains valid values. 


## Question 11
```
Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language
```
A data manipulation language (DML) is used for adding (inserting), deleting, and modifying (updating) data in a relational database. A popular example of a data manipulation language is Structured Query Language (SQL).

There are three general ways you can “manipulate” data in a relational database:
1. You can change which results are presented.
2. You can change how the results are presented or organized (in terms of things like sort order, etc).
3. You can change the underlying data.

The most popular commands for data manipulation in a relational database are:

**SELECT** - retrieve data from the a database </br>
**INSERT** - insert data into a table </br>
**DELETE** - deletes all records from a table (but the space for the records remain) </br>
**UPDATE** - updates existing data within a table

There are three basic relational database **query** operations:  

1. Projection: retrieve selected attributes from a relation 
2. Selection (Restriction): retrieve selected tuples from a relation  
3. Join: combine two or more relations 

And three basic relational database **update** operations: 
1. Add: insert one or more new tuples in a relation 
2. Delete: remove one or more existing tuples from a relation 
3. Change: modify certain data in one or more tuples of a relation 


All relational database **query** operations take one or more relations as input and produce one relation as output, and all relational database **update** operations take one relation as input and produce a modified form of that relation as output.


## Question 12
```
Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language
```

**Quicksort:**  

Quicksort is one of the most famous sorting algorithms based on divide and conquer strategy.  The heart of quicksort is the partition method which runs in linear time. 

The algorithm starts by picking a single item which is called the pivot and then partitions all smaller items before it, and all greater elements in the later portion of the list.  The lesser and greater sublists are then recursively sorted until their size is one or zero - in which case the list is wholly sorted. 

Choosing an appropriate pivot is essential for avoiding severely reduced performance.  Worst case analysis of Quicksort is O(n^2) but if a clever partition is used then it can be optimized and results in anaverage case of O(n log n) complexity.

**Bubble Sort:**

Bubble sort is a sorting algorithm used to sort any type of data structure and is called this because the items go up like bubbles. Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order.

In the Bubble sort algorithm, an array is traversed. It starts from the first element and traverses until the last element. The current element is compared with the next element and if the current element is greater than the next element, it is swapped. This process goes on until the whole array is sorted.

Bubble sort has worst-case and average complexity both О(n²)

**Comparison:**

Quicksort's divide and conquer strategy has an average case of O(n log n) and Bubble sort's brute force approch takes O(n^2).  In comparison, Quicksort is the better algorithm.

## Question 13
```
For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes
```

**Code Snippet:**

```javascript

class Car {
  constructor(brand) {
    this.carname = brand;
  }
  present() {
    return 'I have a ' + this.carname;
  }
}

class Model extends Car {
  constructor(brand, mod) {
    super(brand);
    this.model = mod;
  }
  show() {
    return this.present() + ', it was made in ' + this.model;
  }
}

let makes = ["Ford", "Holden", "Toyota"]
let models = Array.from(new Array(40), (x,i) => i + 1980)

function randomIntFromInterval(min,max) { // min and max included
    return Math.floor(Math.random()*(max-min+1)+min);
}

for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]
  model = models[randomIntFromInterval(0,makes.length-1)]
    
  mycar = new Model(make, model);
  console.log(mycar.show())
}
```