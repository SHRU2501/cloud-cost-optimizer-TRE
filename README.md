#An Aprach to Reducing Cloud Cost & Bandwith using TRE System

## Abstract

This research proposes an approach to reduce cloud costs and bandwidth using the **Traffic Redundancy Elimination (TRE) system**. By leveraging Cloud Computing's Predictive Acknowledgment, impulsive TRE is obtained—minimizing computation and storage costs. A new **Lightweight Chunking Scheme** is introduced to enhance server efficiency and reduce workload. This method benefits cloud users by improving productivity and reducing operational expenses.

---

## Key Concepts

- **Transposition-Reducing Encoding (TRE)** for detecting redundant data blocks.
- **Rabin Fingerprinting** for chunk identification.
- **SHA-based Signatures** for secure and efficient block comparison.
- **Cloud Bandwidth Optimization** using predictive acknowledgment.

---

## Technologies Used

| Component       | Tech Stack                   |
|----------------|------------------------------|
| Backend         | Java (JDK 8+)                |
| Database        | MySQL                        |
| Frontend        | HTML/CSS/JavaScript, Bootstrap *(optional: JSP or Thymeleaf)* |
| Hashing         | SHA-256 for signature generation |
| Fingerprinting  | Rabin fingerprinting logic   |

---



## Signature Generation Using SHA

Secure Hash Algorithm (SHA) is used to generate cryptographic signatures for each file chunk. These signatures identify duplicate blocks, enabling high-efficiency deduplication and reducing unnecessary data transfers. SHA-256 ensures reliability and uniqueness in fingerprinting.


---
 Sample Workflow
'''markdown
1.First run the cloud application:

<img width="800" height="730" alt="Picture2" src="https://github.com/user-attachments/assets/50f41b3d-c037-426c-929a-4c4b5716166b" />


2.Run the client application:

[Uploading Picture1(1).png…]()


3.Click on new user to register as a new user: New user registration screen:

<img width="800" height="730" alt="Picture3" src="https://github.com/user-attachments/assets/5f07aef4-6fe7-45d2-b577-a54e0c695848" />


4.Registering as a new user:

<img width="800" height="730" alt="Picture4" src="https://github.com/user-attachments/assets/4a113aa1-2846-492d-b13a-338805074035" />


5.Click on Upload data to upload the files onto cloud:

<img width="800" height="730" alt="Picture5" src="https://github.com/user-attachments/assets/b6c8b61a-0b2b-4408-80b9-0aa8d77c87d8" />



6.Server screen:


<img width="800" height="730" alt="Picture1" src="https://github.com/user-attachments/assets/a875a91d-cc3e-4d3e-bd35-c5b5e5e22a3d" />



7.The uploaded files will be stored at cloud side
Client can download the data from cloud, to download click on Download Data.


<img width="800" height="730" alt="Picture7" src="https://github.com/user-attachments/assets/e1b7ea89-9f62-43e5-a4a2-406f22b81076" />



8.Server side after downloading the file:
<img width="800" height="730" alt="Picture8" src="https://github.com/user-attachments/assets/17e06496-c8d1-4321-ae90-50e5a04588a7" />


9.Download the same data for next time:
(The same data is already there at local cache so it copies directly from there)
<img width="800" height="730" alt="Picture9" src="https://github.com/user-attachments/assets/b210b65b-6902-4911-bbf3-d69da3eaced2" />


10.Server side:
<img width="800" height="730" alt="Picture10" src="https://github.com/user-attachments/assets/4caed03e-f40f-4251-88e1-50ccfd76c7fd" />



RESULT
<img width="800" height="730" alt="Picture11" src="https://github.com/user-attachments/assets/f587a105-126e-417b-b443-d77e99e8ab8e" />




  README.md
  
  ##License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

