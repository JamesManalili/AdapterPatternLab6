![Adapterpattern](https://github.com/JamesManalili/AdapterPatternLab6/assets/142465145/7257826f-0585-47a5-a78a-ceb46acb4c38)# Problem

__Plugging Devices into Power Outlets__

You are developing an application that helps users manage and control various electronic devices by plugging them into power outlets. Each device has different plug types, voltage, and amperage requirements. To ensure compatibility and safety, you need to create adapters for different devices to allow them to be plugged into standard power outlets.

- __Adaptee Objects:__

  - Laptop - Represents a laptop device that needs to be plugged into a power source. It has the charge() method.

  - Refrigerator - Represents a refrigerator device that requires a power source. It has the startCooling() method.

  - SmartphoneCharger - Represents a smartphone charger that needs to be plugged in for charging. It has the chargePhone() method.

- __Target Object:__

  - PowerOutlet - Represents a standard power outlet with a common interface for plugging in devices. It defines the plugIn() method as the target method.

- __Adapter Objects:__

   - LaptopAdapter - An adapter for plugging a laptop into a standard power outlet. It adapts the Laptop to the PowerOutlet interface, translating plugIn() to charge().

   - RefrigeratorAdapter - An adapter for plugging a refrigerator into a standard power outlet. It adapts the Refrigerator to the PowerOutlet interface, translating plugIn() to startCooling().

   - SmartphoneAdapter - An adapter for plugging a smartphone charger into a standard power outlet. It adapts the SmartphoneCharger to the PowerOutlet interface, translating plugIn() to chargePhone().
 
# UML Class Diagram
![Adapterpattern](https://github.com/JamesManalili/AdapterPatternLab6/assets/142465145/578d1042-b1b0-4d39-9a10-00e54b554374)
