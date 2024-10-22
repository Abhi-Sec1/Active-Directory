# Active Directory Home Lab Project

## Objective
To build a comprehensive home lab environment that includes Active Directory for learning administration and domain management, with Splunk for ingesting and analyzing event data. The lab is set up to support both red and blue team operations, enabling the simulation of real-world attack and defense scenarios.

## Skills Learned
- Hands-on experience with **Active Directory** setup and administration.
- Configuring **Windows Server 2022** as a domain controller.
- Adding and managing domain users and computers.
- Installing and configuring **Splunk** to ingest and analyze telemetry data.
- Conducting **brute-force attacks** using **Kali Linux**.
- Using **Sysmon** to generate detailed event logging.
- Simulating attack scenarios with **Atomic Red Team** and analyzing the generated logs.

## Tools Used
- **Windows Server 2022**: Configured as the Active Directory domain controller.
- **Windows 10**: Joined to the Active Directory domain as a target machine.
- **Kali Linux**: Used as the attacking machine for red team operations.
- **Splunk**: Deployed for log ingestion, security monitoring, and telemetry analysis.
- **Sysmon**: Installed on Windows machines for detailed event logging.
- **VirtualBox**: Used to host virtual machines for the project environment.
- **Atomic Red Team**: Simulated attack scenarios for testing detection capabilities.

## Steps
1. **Part 1**: Created an architecture diagram of the Active Directory lab, showcasing the relationship between the domain controller, target machine, and attacker.
2. **Part 2**: Downloaded and installed the required assets, including Windows Server 2022, Windows 10, Kali Linux, and Splunk using VirtualBox. Created snapshots of the virtual machines.
3. **Part 3**: Installed **Sysmon** for detailed logging on Windows machines and configured **Splunk** as the SIEM to query telemetry data from the domain controller and the target PC.
4. **Part 4**: Set up **Active Directory** on the Windows server, promoted the server to a domain controller, created domain users, and joined the target machine to the domain.
5. **Part 5**: Conducted a **brute-force attack** using Kali Linux on a domain user account and analyzed the telemetry generated by Splunk. Simulated further attacks using **Atomic Red Team** to test detection and response capabilities.

## Architecture Diagram

![Architecture Diagram](https://github.com/user-attachments/assets/4fdfe988-bc53-4b35-a39d-8014ad32b2a4)

---

## References (Step-by-Step Screenshots)
This section includes screenshots for each key part of the project setup, demonstrating the entire process in a visual format.

1. **Splunk Installation and Configuration for Security Monitoring**  
   ![Splunk Setup](https://github.com/user-attachments/assets/08f67d65-5aea-447b-b5af-708f90062952)  

2. **Windows Server 2022 Active Directory Setup**  
   ![AD Setup](https://github.com/user-attachments/assets/8e28228f-a221-47bc-a9ac-8a8d441f9c71) 
   ![AD Setup](https://github.com/user-attachments/assets/c23d331e-b8d2-42dd-87da-2df102cd9ad7)
   ![AD Setup](https://github.com/user-attachments/assets/a82a6e3b-83cd-4814-b1cf-fc343bd01f83)

4. **Sysmon Installation and Configuration for Event Logging**  
   ![Sysmon Setup](https://github.com/user-attachments/assets/aa6a4d79-6046-43fc-aa28-3b9b40e8d50c)
   ![Sysmon Setup](https://github.com/user-attachments/assets/7b8269c5-7550-4184-bbaf-0b2212204845) 

5. **Simulating Cyber Attack Scenarios Using Atomic Red Team**  
   ![Atomic Red Team Simulation](https://github.com/user-attachments/assets/4023aa78-8c65-40bf-b44e-98e7426665c6)
   ![Atomic Red Team Simulation](https://github.com/user-attachments/assets/cb58c383-b6a7-4370-89be-62f329f7e7db)
   ![Atomic Red Team Simulation](https://github.com/user-attachments/assets/4d043090-8a5f-43b7-9cdc-01ffce469d12)
   ![Atomic Red Team Simulation](https://github.com/user-attachments/assets/be40861b-85f4-4af0-83ad-095f402b892d) 


7. **Kali Linux Brute-Force Attack Guide**  
   ![Kali Linux Attack](https://github.com/user-attachments/assets/011aa79c-b6dc-4aef-b275-77dcf19c30e2)
   ![Kali Linux Attack](https://github.com/user-attachments/assets/41ed10ae-e689-47d6-bdc2-d47a24377ab5)




## Future Enhancements
- Adding alerts, dashboards, and reports to **Splunk** for proactive monitoring.
- Expanding the environment to include more advanced attack scenarios and defense techniques.

---

Feel free to clone this repo and build your own Active Directory home lab. If you encounter issues or have improvements, contribute by opening a pull request or leaving a comment.
