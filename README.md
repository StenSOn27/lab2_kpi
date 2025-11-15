# 🧩 Functional and Non-Functional Requirements

### Functional Requirements

| **ID** | **Requirement** | **Description** |
|--------|------------------|------------------|
| **FR1** | User authorization | The system must allow users to securely log in to access their account and personalized features. |
| **FR2** | Reset password | The system must allow users to reset their password in case they forget or lose it. |
| **FR3** | Manage product categories | The admin must be able to create, edit, and delete product categories. |
| **FR4** | Manage products | The admin must be able to add, edit, and delete products in the system. |
| **FR5** | Browse and view products | Users must be able to browse available products and view detailed information about them. |
| **FR6** | Add products to order | Users must be able to add selected products to order. |
| **FR7** | Generate sales report | The admin must be able to generate sales reports for analytical and management purposes. |
| **FR8** | Apply discount | Users must be able to apply valid discount codes to reduce the total order cost. |
| **FR9** | Process payment | The system must securely handle user payments for placed orders. |
| **FR10** | View and manage orders | Users must be able to view


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
| **UC1** | Add categories |
| **UC2** | Edit categories |
| **UC3** | Delete categories |
| **UC4** | Reset password |
| **UC5** | Browse products |
| **UC6** | View product details |
| **UC7** | Add products |
| **UC8** | Edit products |
| **UC9** | Delete products |
| **UC10** | Generate sales report |
| **UC11** | Add to order |
| **UC12** | Place order |
| **UC13** | Apply discount |
| **UC14** | Make payment |
| **UC15** | View orders |
| **UC16** | Update order status |
| **UC17** | Track order status |
---



## **Traceability Matrix (Functional Requirements ↔ Use Cases)**

| **FR \ UC** 	| **UC1** 	| **UC2** 	| **UC3** 	| **UC4** 	| **UC5** 	| **UC6** 	| **UC7** 	| **UC8** 	| **UC9** 	| **UC10** 	| **UC11** 	| **UC12** 	| **UC13** 	| **UC14** 	| **UC15** 	| **UC16** 	| **UC17** 	|
|-------------	|:-------:	|:-------:	|:-------:	|:-------:	|:-------:	|:-------:	|:-------:	|:-------:	|:-------:	|:--------:	|:--------:	|:--------:	|:--------:	|:--------:	|:--------:	|:--------:	|:--------:	|
| **FR1**     	|    X    	|    X    	|    X    	|    Х    	|         	|         	|    X    	|    X    	|    X    	|     X    	|     X    	|     X    	|     X    	|     X    	|     X    	|     X    	|     X    	|
| **FR2**     	|         	|         	|         	|    X    	|         	|         	|         	|         	|         	|          	|          	|          	|          	|          	|          	|          	|          	|
| **FR3**     	|    Х    	|    Х    	|    Х    	|         	|         	|         	|         	|         	|         	|          	|          	|          	|          	|          	|          	|          	|          	|
| **FR4**     	|         	|         	|         	|         	|         	|         	|    Х    	|    Х    	|    Х    	|          	|          	|          	|          	|          	|          	|          	|          	|
| **FR5**     	|         	|         	|         	|         	|    Х    	|    Х    	|         	|         	|         	|          	|          	|          	|          	|          	|          	|          	|          	|
| **FR6**     	|         	|         	|         	|         	|         	|         	|         	|         	|         	|          	|     Х    	|          	|          	|          	|          	|          	|          	|
| **FR7**     	|         	|         	|         	|         	|         	|         	|         	|         	|         	|     Х    	|          	|          	|          	|          	|          	|          	|          	|
| **FR8**     	|         	|         	|         	|         	|         	|         	|         	|         	|         	|          	|          	|          	|     Х    	|          	|          	|          	|          	|
| **FR9**     	|         	|         	|         	|         	|         	|         	|         	|         	|         	|          	|          	|     Х    	|          	|     Х    	|          	|          	|          	|
| **FR10**    	|         	|         	|         	|         	|         	|         	|         	|         	|         	|          	|          	|     Х    	|          	|          	|     Х    	|     Х    	|     Х    	|
