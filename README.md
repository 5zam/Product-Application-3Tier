##  What is 3-Tier Architecture?

**3-Tier Architecture** is a software design approach that organizes the project into **three separate layers**, each with a clear responsibility:

---

### 1️⃣ Presentation Layer (PL)
- This is where **user interaction** happens.
- In ASP.NET Core MVC, it includes:
  - `Controllers`
  - `Views` 
- It **doesn't talk to the database directly**, it only calls services in the BLL.

---

### 2️⃣ Business Logic Layer (BLL)
- Contains the **core logic** of the application.
- Defines:
  - `Interfaces` (contracts)
  - `Services` (implementations)
- It acts as a **bridge** between the views and the data.
- contain Interfaces , Repositories ...

---
### 3️⃣ Data Access Layer (DAL)
- Responsible for all **database interactions**.
- Uses **Entity Framework Core** to:
  - Define `DbContext`
  - Manage `Models` (Entities)
  - Handle `Migrations`
  - `Configuration`
- This layer not contain logic only data-related code
