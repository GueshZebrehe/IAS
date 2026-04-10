🔐 IAS-User Registration System (ASP.NET Core MVC)

##Overview

IAS (Information Access System) is a simple **ASP.NET Core MVC web application** that provides secure user registration functionality.

The system demonstrates:

* User registration with validation
* Password encryption using AES
* SQL Server database integration
* MVC architecture (Model-View-Controller)

##Technologies Used

* ASP.NET Core MVC
* C#
* SQL Server (Express)
* ADO.NET (`SqlConnection`, `SqlCommand`)
* AES Encryption (Custom `AESEncDec` class)
##Project Structure
IAS/
│── Controllers/
│   └── UserController.cs
│── Models/
│   └── User.cs
│── Views/
│   └── User/
│       └── Register.cshtml
│── Helpers/
│   └── AESEncDec.cs
│── appsettings.json
│── Program.cs
---
## ⚙️ Features

* User Registration Form
* Model Validation
* Secure Password Encryption (AES)
* SQL Server Database Storage
* Error Handling with Try-Catch
##How It Works
### Registration Process

1. User fills the registration form
2. Data is validated using `ModelState`
3. Password is encrypted using AES
4. Data is inserted into SQL Server
5. Success or error message is returned
---
##Author

**Zebrehe Guesh**
**Phone Number: 0921990158, Email:zebrheguesh@gmail.com"
---
## License
This project is for educational purposes.
