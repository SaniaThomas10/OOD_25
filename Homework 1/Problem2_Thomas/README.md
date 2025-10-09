# Drone Management System  

**Design Patterns Used:**  
- Factory – creates the different drone types (Surveillance, Delivery, Agricultural)  
- Abstract Factory – each manufacturer (A or B) produces its own family of drones with different specifications  

**Design Choices:**  
The **Factory** pattern was used to centralize the creation of drone types, so adding a new type only requires extending the factory.  
The **Abstract Factory** pattern was used for manufacturers, since each manufacturer provides its own version of each drone type with unique specs (battery, range, features). This cleanly separates the logic for different manufacturers.  

**Extensibility:**  
The system can be easily extended by:  
- **Adding a new drone type** (e.g., RescueDrone): create a new drone class and add it to the Factory and manufacturer factories.  
- **Adding a new manufacturer** (e.g., ManufacturerC): create a new manufacturer factory implementing the same interface with its own specs.  

This design makes it possible to scale without changing the existing codebase significantly.  
