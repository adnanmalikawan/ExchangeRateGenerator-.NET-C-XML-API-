# ExchangeRateGenerator-.NET-C-XML-API-

Developer Information:
Muhammad Adnan Malik  
F20605005 (BSCS Batch 2020)  
National University of Technology (NUTECH)  

Exchange Rate Generator:  
This application enables the generation of queries for retrieving exchange rates. It utilizes data from an external API to create queries based on the fetched information.  

Development Environment:  
- Visual Studio Version: Visual Studio 2022 (Version 17.8.1)  

Installation:  
1. Download this folder to your local machine.
2. Open the solution file (“Testing.sln”) in Visual Studio.
3. Build the solution by selecting “Build” > “Build Solution” from the menu, or by pressing “Ctrl + Shift + B”.
4. Run the application by pressing “F5” or selecting “Debug” > “Start Debugging”.  

Usage:  
1. Launch the application after successful installation.
2. Choose a currency from the dropdown list.
3. Specify a start date and an end date for the exchange rate data.
4. Click the "Generate Queries" button to create queries.
5. The generated queries will be displayed in the text box below.

Configuration:  
Before running the application, ensure to set your API key in the “Form1.cs” file:
csharp:
private const string API_KEY = "YOUR_API_KEY_HERE";

Replace "YOUR_API_KEY_HERE" with your actual API key. You can obtain an API key from https://api.exchangeratesapi.io. 

Dependencies:  
- Newtonsoft.Json: Utilized for parsing JSON responses from the API.
- System.Net.Http: Used for making HTTP requests to the API.
- System.Windows.Forms: Employed for creating the user interface.

These dependencies are already included in the project and managed through NuGet.

Acknowledgements:  
- This application utilizes the Exchange Rates API from (https://api.exchangeratesapi.io) for fetching exchange rate data.





Enjoy your experience! 😊
