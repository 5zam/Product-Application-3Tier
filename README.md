##  Identity Framework + ApplicationUser + Auth Controllers

**ASP.NET Core Identity** is used to manage authentication, authorization and user accounts securely

---

### ✅ What is ASP.NET Core Identity?

ASP.NET Core Identity is a membership system that allows you to:
- Register and log in users
- Manage roles and claims
- Secure your APIs using authentication and authorization

It handles all the essential features for user security including:
- Password hashing
- Token generation
- Lockouts, two-factor authentication, email confirmation, etc.

---

### 👤 ApplicationUser

Instead of using the default `IdentityUser`, we create a custom user model by inheriting from `IdentityUser` so by this we can use such as `UserName`, `Email`, `PhoneNumber`, etc

like this:
![example](https://github.com/user-attachments/assets/d893001a-1644-4390-8791-1fa4fc7a268e)

