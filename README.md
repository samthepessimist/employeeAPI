## EmployeeApp API

The EmployeeApp API is a simple RESTful backend application designed to manage employee data while reinforcing core object-oriented programming principles. The system allows for the creation, retrieval, and management of employee records through well-structured domain models and standard getter and setter methods. Each Employee object encapsulates its attributes such as id, name, position, and salary, ensuring proper data hiding and controlled access through accessor and mutator methods. This design promotes clean code practices and demonstrates the importance of encapsulation in building maintainable APIs.

### Composition

A key focus of the project is the practical implementation of composition. In this API, an Employee strongly owns certain dependent objects, such as an Address or Profile component, meaning these objects cannot meaningfully exist without the employee. The lifecycle of these composed objects is tightly bound to the Employee, reinforcing the concept of strong relationships between classes. This approach improves cohesion and ensures that related data remains structured and logically grouped within the application.

### Aggregation

In addition to composition, the project also demonstrates aggregation by modeling relationships where objects can exist independently. For example, an Employee may be associated with a Department entity that exists separately within the system. Multiple employees can reference the same department without controlling its lifecycle. This distinction between composition and aggregation provides practical exposure to real-world object relationships and strengthens understanding of object-oriented design principles within a REST API context.
