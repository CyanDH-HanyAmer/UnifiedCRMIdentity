# UnifiedCRMIdentity 🚀

A modern, scalable **CRM and Identity Management System** built with **.NET 9**, **Blazor WebAssembly**, and **MongoDB/SQL/PostgreSQL**. This solution follows **Clean Architecture** and supports **localization (Arabic & English)**.

## 🌟 Features

### ✅ Identity Management
- User Registration & Authentication
- Role & Permission Management
- Multi-Factor Authentication (2FA/MFA/OTP)
- Trusted Devices & Email Confirmation
- Secure Login & Logout with Activity Logs

### ✅ CRM System
- Lead & Customer Management
- Task & Activity Tracking
- Opportunity Pipeline
- Dynamic Localization (UI & Data)

### ✅ Architecture Highlights
- **Clean Architecture**: Separation of concerns with Domain, Application, Infrastructure & Presentation layers.
- **CQRS + MediatR**: Efficient command and query handling.
- **Multi-Database Support**: Works with **MongoDB, SQL Server, PostgreSQL**.
- **Localization Support**: Database & UI localization for multiple languages.

## 📂 Project Structure
```
UnifiedCRMIdentity
│── src
│ ├── Domain                # Core business logic (Entities, Events, Value Objects) 
│ ├── Application           # CQRS, Services, DTOs 
│ ├── Infrastructure        # Database & External Services 
│ ├── Presentation          # Blazor WebAssembly & API Controllers 
│── tests                   # Unit & Integration Tests 
│── README.md               # Project Documentation 
│── LICENSE                 # Open Source License
```
## 🛠️ Tech Stack

- **Backend:** .NET 9, C#, MediatR, CQRS
- **Frontend:** Blazor WebAssembly
- **Database:** MongoDB, SQL Server, PostgreSQL
- **Authentication:** .NET Identity, JWT, 2FA
- **Localization:** Resx files & Dynamic Database Localization

## 🚀 Getting Started

### 🔹 Prerequisites
- .NET 9 SDK
- MongoDB / SQL Server / PostgreSQL
- Node.js (for Blazor dependencies)

### 🔹 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/UnifiedCRMIdentity.git
   cd UnifiedCRMIdentity
   ```
2. Configure the database in appsettings.json:
   ```json
   {
     "Database":
       {
         "Provider": "MongoDB",  // Change to "SQLServer" or "PostgreSQL"
         "ConnectionString": "your-connection-string"
       }
   }
   ```
3. Run the application:
   ```sh
   dotnet run --project src/Presentation/UnifiedCRMIdentity.API
   ```
<!-- LICENSE -->
## 📜 License
This project is licensed under the MIT License.

<!-- CONTRIBUTING -->
## 🤝 Contribution
We welcome contributions! Feel free to submit issues and pull requests.

<!-- CONTACT -->
## Contact

Hany Amer - [in/hany-amer-saad](https://www.linkedin.com/in/hany-amer-31534129) - hany.amer.saad@gmail.com
