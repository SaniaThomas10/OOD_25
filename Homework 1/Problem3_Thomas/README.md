# Product Customization & External Integration System  

**Design Patterns Used:**  
- Builder – used for creating customizable products (Laptops and Smartphones) step by step, with a fixed price of $800 for all custom builds.  
- Adapter – used to connect and convert supplier CSV data into the system’s internal Product objects.  

**Design Choices:**  
The **Builder** pattern was chosen because products like laptops and smartphones have many optional specifications, and step-by-step building makes them easier to configure without long constructors.  
The **Adapter** pattern was chosen to handle differences between the supplier’s CSV format and the internal product model, making integration smooth and flexible.  

  ![0](https://github.com/user-attachments/assets/a94b39da-5775-4625-97d1-b7f5ee22466a)

