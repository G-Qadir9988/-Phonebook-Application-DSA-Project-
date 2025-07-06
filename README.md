# 📞 Phonebook Application (DSA Project)

## 🌟 Overview

A **Data Structures and Algorithms (DSA)** based **Phonebook Management System** developed in **C++**, using **singly linked lists** and **stack** data structures.  
This application allows users to efficiently store, search, and delete contacts, as well as maintain a call log and suggest contacts based on name prefixes.

---

## 👥 Team Members

| Name            | Contact                                      |
|------------------|----------------------------------------------|
| **Ghulam Qadir** | 📧 gqitspecialist@gmail.com <br> 🔗 [LinkedIn](https://www.linkedin.com/in/ghulam-qadir-07a982365) |
| **Noor Malik**   | 🔗 [LinkedIn](https://www.linkedin.com/in/noormalik56500) |
| **Ishrat Ali**   | —                                            |

---

## 🚀 Project Overview

The **Phonebook App** uses:
- **Singly Linked Lists** to manage contacts and multiple phone numbers
- **Stacks** to maintain a runtime log of **recently dialed contacts**

### Key Operations:
- Add and delete contacts  
- Store multiple numbers per contact  
- Log and view recent calls  
- Recommend contacts using prefix-based string matching  

---

## ⚙️ Technologies Used

- **Language:** C++  
- **Programming Paradigm:** Procedural  
- **DSA Concepts Implemented:**
  - Singly Linked List – for contact & phone number chaining  
  - Stack – for recent call tracking (LIFO)  
  - Linear Search – for contact retrieval  
  - String Matching – for recommendations  

---

## 🧩 Features

### ✅ Add Contact
- Input contact name and multiple numbers  
- Contact nodes linked with lists of numbers  

### 📃 Display All Contacts
- Print all saved contact names and associated numbers  

### ❌ Delete Contact
- Search and delete contact along with associated numbers  

### 📞 Make a Phone Call
- Log a call to a contact by name  
- Push contact to the recent calls stack  

### 🔁 Recently Dialed
- Show all previously called contacts (LIFO order)  
- Maintains temporary runtime call history  

### 🔍 Recommendation Engine
- Suggest contacts based on typed prefix  
- Efficient prefix-based matching  

---

## 🧠 DSA Concepts Applied

| Concept        | Use Case                             |
|----------------|--------------------------------------|
| Linked List    | Contact and phone number management  |
| Stack          | Recently dialed call tracking        |
| Dynamic Memory | Node allocation and deletion         |
| String Matching| Prefix-based contact suggestions     |

---

## 📷 Sample Functional Flow

Phonebook App:

Add Contact

Display Contacts

Delete Contact

Make a Call

Recently Dialed

Recommend Contact

Exit


---

## 📜 License

This project is open-source and available for **educational and academic use** under the **MIT License**.

---

## 📧 Contact

For inquiries or feedback:

- **Ghulam Qadir** — 📧 gqitspecialist@gmail.com  
- **Noor Malik** — 🔗 [LinkedIn](https://www.linkedin.com/in/noormalik56500)


## 📦 How to Run

### ✅ Compile
```bash
g++ -o phonebook phonebook.cpp

./phonebook

## 📈 Complexity Analysis

| Operation         | Time Complexity                             |
|-------------------|----------------------------------------------|
| **Add Contact**    | O(1) per contact/number                     |
| **Delete Contact** | O(n) search and delete                      |
| **Display Contacts** | O(n + m), where m = total phone numbers  |
| **Make a Call**    | O(n) search + O(1) push to stack            |
| **Recently Dialed**| O(k), where k = stack size                 |
| **Recommendation** | O(n * p), where p = prefix length          |

---

