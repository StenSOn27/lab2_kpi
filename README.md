### Lab2

### Functional Requirements

| **ID** | **Requirement** | **Description** |
|--------|------------------|------------------|
| **FR1** | User authorization | The system must allow users to log in to access all features. |
| **FR2** | Reset password | The system must allow users to reset their password if needed. |
| **FR3** | Manage product categories | The admin must be able to create, edit, and delete product categories. |
| **FR4** | Manage products | The admin must be able to add, edit, and delete products. |
| **FR5** | Browse and view products | Users must be able to browse product listings and view product details. |
| **FR6** | Add products to order | Users must be able to add selected products to their order. |
| **FR7** | Generate sales report | The admin must be able to generate sales reports. |
| **FR8** | Apply discount | Users must be able to apply discount codes to their order. |
| **FR9** | Process payment | The system must securely process payments through the payment service. |
| **FR10** | View and manage orders | Users can view their orders; admins can update order status; users can track status. |


## **2. Non-Functional Requirements**

| № | Category | Requirement |
|---|-----------|-------------|
| NFR1 | Performance | The system must respond to user actions within 2 seconds. |
| NFR2 | Reliability | The system must save all order and payment data correctly. |
| NFR3 | Security | Only registered users can place orders or make payments. |
| NFR4 | Usability | The interface must be clear and intuitive for users. |
| NFR5 | Maintainability | The system should be easy to update and expand by adding new features. |

### Use Cases

| **ID** | **Use Case Name** |
|--------|--------------------|
| **UC1** | Authorization |
| **UC2** | Reset password |
| **UC3** | Manage categories |
| **UC4** | Manage products |
| **UC5** | Generate sales report |
| **UC6** | Browse products |
| **UC7** | View product details |
| **UC8** | Add to order |
| **UC9** | Place order |
| **UC10** | Apply discount |
| **UC11** | Make payment |
| **UC12** | View orders |
| **UC13** | Update order status |
| **UC14** | Track order status |



## **Traceability Matrix (Functional Requirements ↔ Use Cases)**

| **FR \ UC** | UC1 Auth | UC2 Reset | UC3 Manage Cat | UC4 Manage Prod | UC5 Report | UC6 Browse | UC7 View | UC8 AddToOrder | UC9 PlaceOrder | UC10 ApplyDisc | UC11 Pay | UC12 ViewOrd | UC13 UpdateStat | UC14 Track |
|-------------|:--------:|:---------:|:---------------:|:----------------:|:----------:|:----------:|:--------:|:--------------:|:--------------:|:--------------:|:--------:|:------------:|:---------------:|:----------:|
| **FR1 Authorization** | X | X | X | X | X | X | X | X | X | X | X | X | X | X |
| **FR2 Reset password** |   | X |   |   |   |   |   |   |   |   |   |   |   |   |
| **FR3 Manage categories** |   |   | X | X | X | X | X | X | X | X | X | X | X | X |
| **FR4 Manage products** |   |   |   | X | X | X | X | X | X | X | X | X | X | X |
| **FR5 Browse & view products** |   |   |   |   |   | X | X |  |  |  |  |  |  |  |
| **FR6 Add products to order** |   |   |   |   |   |   |   | X | X |  |  |  |  |  |
| **FR7 Generate sales report** |   |   | X | X | X |   |   |   |   |   |   |   |   |   |
| **FR8 Apply discount** |   |   |   |   |   |   |   | Х | X | X |   |   |   |   |
| **FR9 Process payment** |   |   |   |   |   |   |   |   | X |   | X |   |   |   |
| **FR10 View & manage orders** |   |   |   |   |   |   |   |   | X |   | X | X | X | X |
