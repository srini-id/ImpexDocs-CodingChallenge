# ImpexDocs-CodingChallenge

## Background Information

ImpexDocs is a leading provider of import and export documentation. The product is designed to help streamline the overall process with shipping, sales, invoicing etc.

You have been given the task to build out an initial working prototype of the next generation SaaS solution for ImpexDocs. You will need to be able to demonstrate your abilities as a full stack developer working on the code base as if it will be going out into production.

We anticipate the task to take you approximately 8-10 hours to complete but may possibly take you more based on how far you wish to go.

### What we are looking for

1. Attention to detail. You will need to carefully read through the requirements and constraints and make sure to comply with that
2. Quality of code. This is your chance to shine as a Software Engineer. You need to demonstrate your breadth of knowledge. Things we look for include 
  - Code structure (think through how many projects in the solution, what is the structure, what architecture you will use etc)
  - Automated tests (unit, integration etc)
  - Scalability of solution
  - Security aspects
  - Extensibility of code (think about the framework you will use , e.g. n-tier, DDD etc)
  - SOLID principles in action
3. How you develop APIs (using good practices such as pagination, RESTful in nature etc)
4. Breadth of knowledge in the field. We want you to showcase how much you understand in the area of software development. You want to really use this to showcase the various talents you have (e.g. you might want to showcase your ability in running services in a container, or how you would do a CICD pipelines for your solution)
5. How you maintain the source code (checkins, commit messages, branching etc are all part of the process). Make sure to demonstrate your abilities if this was code you are delivering to production.

### Constraints

The main constraints we have on this solution is that it shall be a `.NET Core` backend. You will need to provide a readme documentation to your file on how to execute and have it run by our Engineers. Check your code into a public git repository and share the repository with read access to the public.

*If your code does not build or we can not get it to run based on your instructions, we will not be going any further.*

Your front end and datalayer can be any technology you wish. Choose this wisely as you may want to build certain tests associated with the code so the technology choice can become important.

## Requirements

1. You will be required to create three different screens
  - Screen 1 - Login page
  - Screen 2 - Shipment summary page which shows a list of all the available shipments on the page
  - Screen 3 - Page showing the full details of any one of the shipment that is selected from screen 2
2. Only logged in users should be able to access screen 2 and screen 3. If the user failed authentication, there should be adequate messaging
3. Each user belongs to only one company. When a user logs in successfully, they will see the details of all the shipments for that company. To verify this, you will need to create at MINIMUM, two users and two companies, to verify that appropriate data is returned for the user. 
4. Shipment Summary page (Screen 2) will be a readonly view of all several fields of a shipment (See `DummyData.xlsx` for more info)
  - A grid should be available to display all the shipment details
  - You should use the `DummyData.xlsx` as inputs. You are encouraged to add more rows to the dummy data as you wish
  - You should expose some way to edit a shipment details from the list. Clicking on it shouild take you to screen 3
  - You should expose some way to delete a single entry in the shipment details
5. Screen 3 should be the full details of the Shipment. All fields except the `CompanyID` should be editable
  - A save button should be exposed that saves the changes
  - A delete button should be exposed that deletes that entry and returns back to Screen 2 

