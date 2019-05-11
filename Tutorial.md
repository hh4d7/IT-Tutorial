[Go Back](README.md)

### History of Bluetooth
 - ##### How Bluetooth got its name.
   In 1996, three industry leaders, Intel, Ericsson, and Nokia, met to plan the standardization of this short-range radio technology to support connectivity and collaboration between different products and industries.
   During this meeting, Jim Kardash from Intel suggested Bluetooth as a temporary code name. Kardash was later quoted as saying, “King Harald Bluetooth…was famous for uniting Scandinavia just as we intended to unite the PC and cellular industries with a short-range wireless link.”
- ##### Secret behind the logo
  The Bluetooth logo is a bind rune merging the Younger Futhark runes Runic letter ᚼ(Hagall) and Runic letter ᛒ(Bjarkan), King Harald's initials.
![](https://cdn.windowsreport.com/wp-content/uploads/2017/01/pc-bluetooth-windows-10-1024x1024.png)

### What is Bluetooth technology
Bluetooth is a wireless technology standard for exchanging data between fixed and mobile devices over short distances using short-wavelength UHF radio waves in the industrial, scientific and medical radio bands, from 2.400 to 2.485 GHz, and building personal area networks (PANs). 
### How does Bluetooth work
Bluetooth devices can aotomatically detect and then connect to another device when user request. Each pair of devices randomly pick one of the 79 available channels centered on 2.45 GHz when setting up connection. Pairs of devices also constantly shift the channel they are using, so the risk of interference form other electrical devices can be minimized. 
When a group of  Bluetooth devices are exchanging information together, they create a network called a piconet.One device (known as the master) acts as the overall controller of the network, while the others (known as slaves) obey its instructions.
- ##### Pairing and bonding
  For security reasons, it is necessary to recognize specific devices when setting up connection. Meanwhile, it is convenient for devices to be able to connect without user intervention (for example, as soon as in range). Pairing and Bondling process is designed to solve the conflict.
  >The pairing process is triggered either by a specific request from a user to generate a bond (for example, the user explicitly requests to "Add a Bluetooth device"), or it is triggered automatically when connecting to a service where (for the first time) the identity of a device is required for security purposes.

  After the pairing process completed, a bond betweeen the two devices are aotomatically formed. Those two devices can connect to each other without repeating the pairing process. User can exist the bondling relationship at anytime. 
- ##### Pairing mechanisms
  >Legacy pairing: This is the only method available in Bluetooth v2.0 and before. Each device must enter a PIN code; pairing is only successful if both devices enter the same PIN code. 
  Secure Simple Pairing (SSP): This is required by Bluetooth v2.1. Secure Simple Pairing uses a form of public key cryptography, and some types can help protect against man in the middle, or MITM attacks.
- ##### One thing you should know when setting up connections
  Every device has a unique 48-bit address that is generally not shown. Instead, friendly Bluetooth names are used, which can be set by the user. This name appears when another user scans for devices.

### Versions of Bluetooth 
- Bluetooth 1.x (1998)
  -Maximum Speed: 723.1 Kbit/s, Maximum Range: 10 meters
  
  The first version of Bluetooth used a modulation scheme called Gaussian Frequency Shift Keying (GFSK). With GFSK, the modulated carrier shifts between two frequencies representing 1s and 0s.

- Bluetooth 2.x+EDR (2004)
  -Maximum Speed: 2.1 Mbit/s, Maximum Range: 10 meters
 
  The main difference is the introduction of an Enhanced Data Rate (EDR) for faster data transfer.EDR can provide a lower power consumption through a reduced duty cycle.

- Bluetooth 3.x+HS (2009)
  -Maximum Speed: 24 Mbit/s, Maximum Range: 10 meters

  Bluetooth 3.0 further improved data speeds up to 24 Mbps of data transfer. The results were game-changing. Short-range wireless solutions could now provide reliable, high speed connection.

- Bluetooth 4.x (2010)
  -Maximum Speed: 24 Mbit/s, Maximum Range: 50 meters
  
  Bluetooth 4 introduced low-power Bluetooth Low Energy, previously know as Wibree, branded as "Bluetooth Smart." It was designed to meet the increasing demand for wireless connection between small devices.

- Bluetooth 5.x (2016)
  -Maximum Speed: 48 Mbit/s, Maximum Range: 300 meters
  
  Bluetooth 5 provides options that can double data rate or fourfold range. Bluetooth 5.0 also introduced new features that foucus on emerging Internet of Things.

 #### Bluetooth vs. Wi-Fi
  Bluetooth and Wi-Fi both are designed to set up networks and tranfer data or files between devices. Wi-Fi is developed as a a replacement for high-speed cabling for general local area network access. Bluetooth is a replacement for cabling in a variety of personally carried devices. If tranferring speed is not an problem, Bluetooth is more useful when echange data between personal mobile devices that are close to each other. 
  
  #### security concerns
  - ##### Bluejacking 
    >It happens when unsolicited messages are sent to discoverable Bluetooth devices. Bluejacking is often used to send spam messages to people, and the sender does not gain control over the recipient’s device.
  - ##### Bluebugging
    >In bluebugging, attackers take control of Bluetooth devices without the user’s knowledge. Bluebuggers target devices that are in discoverable mode, and older devices with out-of-date firmware are especially susceptible. Once thieves gain control over a device, they can access sensitive information like a victim’s contacts, photographs, and more.
- ##### Blueborne
  >Blueborne is an attack vector that was revealed by the security firm Armis in 2017. Endangering desktop, mobile, and IoT operating systems like Windows, Android, iOS, and Linux. Blueborne attacks do not require pairing nor do they require devices to be set in discoverable mode. Once attackers successfully access a Bluetooth device, they can complete takeovers of devices.

- #### Tips for maintaining safety
   The easiest preventative way is to *turn off* Bluetooth on your devices when you do not need to connect other devices. Cyber thieves cannot target your devices if your Bluetooth connectivity is off.
   Also, it is important to keep updating Bluetooth driver, wchih might close off potential exploit loops.

[回到顶部](#readme)
For more information: 
[Wikipedia](https://en.wikipedia.org/wiki/Bluetooth#Devices),[Cybrary](https://www.cybrary.it/2018/07/bluetooth-security-risks/)

[Go Back](README.md)
