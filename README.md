# Breadboard-Vending-Machine
In this page you will have the information to create a Breadboard Vending Machine. You will learn everything you need to create one, From pieces you need to photos to see where the parts go.

In the next circuit you can see two inputs, a "coin" button and a "vend" button. When you press on the coin button it represents inserting a coin, when you press the vend button, the machine will vend an item. ( the circuit will turn on a LED representing vending an item). Also, you will see two LED outputs, the coin LED and the vend LED. The coin LED will turn on when a coin has been inserted and the vend LED indicates that an item has been vended. For the machine to vend an item, first, we need the user to insert a coin and after this happen we would expect the circuit to reset itself and go back to the "no coin" state.

![image](https://github.com/user-attachments/assets/ebbe9793-a558-4c9f-811c-12d541daa25e)

When you press the coin button, the coin memory device will store the fact that a coin was inserted, the memory device output would be 1, indicating that a coin hass been inserted, and the coin LED will lights up. If a coin was previously inserted, when you prees the vend button , the AND gate ouput would be 1 and the vend LED turn on. But, if you press the vend button without previously inserting a coin, nothing will happen. And to clear the coin LED and reset the circuit, you must manually set the reset input to 1.

#How to add delay to the circuit?

![image](https://github.com/user-attachments/assets/21c1af83-aee1-44ff-8298-80d1389eaa4a)

A capacitor is an electrical component that stores energy, it has 2 terminals. When the current flows to the capacitor, the capacitor will charge, this ability is called capacitance which is measure in farads. One farad is a very large value, so we tipically rate capacitors in microfarads (uF). When the capacitor is not charged it acts like a short circuit. Once the capacitor is charged, it acts like an open circuit. The time it takes to charge or discharge a capacitor is controlled by the capacitor's capacitance value and resistance in the circuit.

![image](https://github.com/user-attachments/assets/573e951d-4d0b-4148-8f17-70cd9353e6a0)

#Example:

![image](https://github.com/user-attachments/assets/ef53e311-6419-47ab-a5b9-8cfaa301fda8)

#Real Circuit

![WhatsApp Image 2025-02-27 at 16 21 25_2d7818f3](https://github.com/user-attachments/assets/eb849cbe-736f-4b43-83ee-51a92dc53209)

![WhatsApp Image 2025-02-27 at 16 21 25_21395376](https://github.com/user-attachments/assets/ef9e72be-0986-4f51-9801-7dada1227531)

![WhatsApp Image 2025-02-27 at 16 21 25_5474ef94](https://github.com/user-attachments/assets/26d03d07-212a-4220-a691-31d1e3e3c696)

#Old School Vending Machine

![image](https://github.com/user-attachments/assets/50735d34-7129-4593-a882-0260f4b5ccc8)

Old-school vending machines, like the classic Coca-Cola machines from the 1950s, used electromechanical systems to process coins and dispense items. Our breadboard vending machine simplifies this by using basic digital logic components like switches, LEDs, and an SR latch. Instead of motors and sensors, our design uses logic gates to control when an item is dispensed. This project is a small-scale, educational version of how vending machines function at their core.


#Refrence 

Nadaletomas. (n.d.). GitHub - nadaletomas/vendingmachinepage. GitHub. https://github.com/nadaletomas/vendingmachinepage

Ashvnv. (n.d.). GitHub - ashvnv/smart-vending-machine: Vending machine with voice assistance. GitHub. https://github.com/ashvnv/smart-vending-machine

Tdowner. (n.d.). GitHub - tdowner93/Breadboard-Vending-Machine-Portfolio-Page. GitHub. https://github.com/tdowner93/Breadboard-Vending-Machine-Portfolio-Page/tree/main



# Raspberry-Pi-Vending-Machine

# Raspberry Pi

A Raspberry Pi is a small, low-cost computer that you can use for many different projects, like building a robot, creating a home media center, or learning to code. It works like a regular computer—you can connect a monitor, keyboard, and mouse to it—but it's much smaller and cheaper. People use it for fun DIY projects, education, and even advanced tech applications!

# Creating A Vedning Machine

In this picture, we are putting together the breadboard which basically works as the visualization for what we code to the Raspberry Pi.

![image](https://github.com/user-attachments/assets/32e6ab4a-540d-498f-ac7a-8e392efe3b95)

![image](https://github.com/user-attachments/assets/125c8514-1be9-41b7-b7c8-d0ec5dca4484)

# Diagrams

![image](https://github.com/user-attachments/assets/78b2e6c6-5b5b-48d5-be45-d147ef773cde)

![image](https://github.com/user-attachments/assets/9b278c8a-7075-4458-ab7d-da323aae20a0)

# LED On

![image](https://github.com/user-attachments/assets/6619a5c1-b665-4cc5-9ca1-d48481a4bc30)

# LED Off

![image](https://github.com/user-attachments/assets/d888f25d-5c87-424c-8fda-e8d4b857929c)

# References
Justice, M. (2021). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine. No Starch Press.

AuctionZip. (n.d.). Vintage 1960's Coca-Cola Cavalier CS-64 Vending Machine Professional Restoration. Retrieved February 27, 2025, from https://www.auctionzip.com/auction-lot/vintage-1960-s-coca-cola-cavalier-cs-64-vending-m_5974FD4AB6/








