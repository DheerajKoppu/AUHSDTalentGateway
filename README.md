# The AUHSD Talent Gateway
The AUHSD Talent Gateway is a .NET-based program designed to revolutionize the job market. It provides communication with the users of the program, letting them know every step of their application. It essentially makes the job application industry much more transparent while maintaining numerous features such as having a profile, submitting videos, photos, resume, and more. It sends emails to the users regarding their application as well as has the ability for admins to delegate the applications to different HR and Interview Panels. This program essentially aims in making the Job Application process as streamlined and accessible for employees and employers.

## Requirements
- Operating system: Windows
- Microsoft SQL Server Management Studio 19 installed
- Microsoft Visual Studio 2022 installed
- Web browser (Google Chrome, Mozilla Firefox, etc.)

## Installation

### 1. Access source code:

1.1. Clone or download code from GitHub repository
  - Clone the code from GitHub onto your local Visual Studio
  - Download the ZIP file with all program files and unzip
<img width="468" alt="image" src="https://user-images.githubusercontent.com/67035348/232840991-a8c0ab5b-c03d-436b-bc5e-4edbfbb35197.png">


1.2. Open the source code in your local IDE
  - Navigate to FBLA.sln located in "C:\Users\\**<YOUR_USERNAME>**\Downloads\AUHSD Talent Gateway\FBLA_JOB_PORTAL\FBLA_JOB_PORTAL.sln"

### 2. Install required packages and modules:

2.1. Open a project in Visual Studio

2.2. Right-click on the project name and click Manage NuGet Packages

2.3. In the Browse Section, install the following if not already installed:

- DocumentFormat.OpenXml
- System.ValueTuple
- System.Threading.Tasks.Extensions
- System.Runtime.CompilerServices.Unsafe
- System.Numerics.Vectors
- System.Memory
- System.Diagnostics.DiagnosticSource
- System.Buffers
- Microsoft.Extensions.Primitives
- Microsoft.Extensions.Options
- Microsoft.Extensions.Logging.Abstractions
- Microsoft.Extensions.Logging
- Microsoft.Extensions.DependencyInjection.Abstractions
- Microsoft.Extensions.DependencyInjection
- Microsoft.CodeDom.Providers.DotNetCompilerPlatform
- Microsoft.Bcl.AsyncInterfaces

### 3. Run the program:

3.1. Open the FBLA_JOB_PORTAL.sln file in Visual Studio

3.2. Ensure all NuGet packages are installed as mentioned in Step 2

3.3. Press F5 or click on the green triangle to build and run the application

### 4. Set up the SQL Server and Database:

4.1. Connect to the SQL Server with your credentials

4.2. Create a New Database called Job Portal in SQL Server Management Studio
  - Right-click on Databases and select Restore Database
  - Select Device for the source and click on the '...' button
  - Select "Add" for the source and click on the "..." button and navigate to the path of the SQL backup
  - Typically, the path would be "C:\Users\\**<YOUR_USERNAME>**\Downloads\AUHSD Talent Gateway\FBLA_JOB_PORTAL\JobPortal"
  - Click "Ok" and "Ok" again and follow the prompts to create the database

4.3. If you would like to erase all the data from the tables, use the command `truncate <TABLE NAME>` on every table.

4.4. To establish a connection between Dotnet and SQL, update the connection string ID within the Web.Config file with your own login credentials

## Usage

- Use the program to apply for jobs.
- Use the program to add jobs to allow prospective employees to apply.
- Manage users of the program in a very effective manner.
- Send emails to prospective employees.
- Delegate tasks upon interviewing candidates.

## Credits

The AUHSD Talent Gateway was developed by Dheeraj Koppu for the 2024 FBLA Website Coding and Development Event. Dheeraj is a junior at Cypress High School. The source code for the program is available on Github at [https://github.com/DheerajKoppu/AUHSDTalentGateway.git](https://github.com/DheerajKoppu/AUHSDTalentGateway.git). If you have any questions or suggestions, please contact him at [auhsdtalentgateway@gmail.com](mailto:auhsdtalentgateway@gmail.com).
