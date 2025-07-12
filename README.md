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

  
