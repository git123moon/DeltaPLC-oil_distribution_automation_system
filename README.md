# **Oil Distribution Automation System**

## **Overview**
This project automates the oil distribution process using **Delta PLC**, **HMI**, and **solenoid valves**. The system enables efficient and precise oil dispensing by utilizing a QR code-based mechanism for oil type and volume identification.

---

## **Key Features**

### **HMI 1: QR Code Generation**
- Operators input oil type and volume through the first HMI, which generates a unique QR code containing these details.

### **HMI 2: QR Code Scanning**
- The second HMI integrates with a QR code scanner to read the QR code and extract oil type and volume data.

### **Automated Oil Dispensing**
- The system uses PLC logic to activate the appropriate solenoid valve and dispense the specified volume of oil based on the scanned QR code.

### **Real-Time Monitoring**
- Displays system status and dispensing progress on the HMI.

### **Error Handling**
- Alerts are generated for invalid QR codes or mismatched data to ensure accurate operations.

---

## **System Components**

### **Hardware**
- **Delta PLC:** DVP series for controlling the process.
- **Delta HMI:** DOP-100 series for user interface and QR code generation.
- **Solenoid Valves:** For routing oil based on type.
- **QR Code Scanner:** For reading encoded data from QR codes.
- **Power Supply Unit:** 12V DC for motor and system components.

### **Software**
- **WPLSoft:** For PLC programming.
- **DOPSoft:** For HMI design and configuration.

---

## **How It Works**

### **1. Data Input and QR Code Generation**
- Operators input the oil type and required volume on HMI 1.
- A unique QR code is generated based on the input.

### **2. QR Code Scanning and Data Extraction**
- HMI 2 uses a QR code scanner to read and extract the encoded oil type and volume.

### **3. PLC Logic Execution**
- The Delta PLC processes the scanned data, matches the oil type, and activates the corresponding solenoid valve.
- The exact volume is dispensed using timers or flowmeters for precision.

### **4. Error Handling**
- Invalid or mismatched QR codes trigger alerts for corrective action.

---

## **Contributing**
Feel free to contribute by forking the repository and submitting pull requests with improvements or feature additions.

---

## **Contact**
For any questions or issues, please contact the project contributors via GitHub.



