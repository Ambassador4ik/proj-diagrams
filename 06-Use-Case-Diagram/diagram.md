graph LR
     Admin[Admin] --> G(View Calculation History)
     Admin --> H(Manage Data)
 
     User[User] --> A(Enter Calculation Input)
     User --> B(Upload File for Multi-Calculation)
     A --> C(Compute Break-Even Points)
     C --> D(View Calculation Results)
     C --> E(Save Calculation History)
     B --> F(Perform Batch Calculations)
     F --> D
     F --> E