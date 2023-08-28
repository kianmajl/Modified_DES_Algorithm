<h1>
<br>Modified_DES_Algorithm
</h1>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📂 Project Structure](#-project-structure)
- [🔎 Details of Codes](#-details-of-codes)
- [🤝 Collaborators](#-collaborators)


---
## 📍 Overview

In this repository, you'll find an implementation of a modified version of the Data Encryption Standard (DES) algorithm. DES is a widely known symmetric-key block cipher that operates on 64-bit blocks of data and employs a 56-bit key.

---


## 📂 Project Structure

 * [DES.ipynb](./DES.ipynb)
 * [Problem Statement.pdf](./Problem%20Statement.pdf)
 * [README.md](./README.md)
 * [expansion_p_box.txt](./expansion_p_box.txt)
 * [final_permutation.txt](./final_permutation.txt)
 * [initial_permutation.txt](./initial_permutation.txt)
 * [key tablea_S-BOX_P-BOX.txt](./key%20tablea_S-BOX_P-BOX.txt)
 * [key_compression.txt](./key_compression.txt)
 * [known_ciphertext.txt](./known_ciphertext.txt)
 * [known_plaintext.txt](./known_plaintext.txt)
 * [pair.txt](./pair.txt)
 * [parity_bit_drop.txt](./parity_bit_drop.txt)
 * [sbox.pkl](./sbox.pkl)
 * [shift_table.txt](./shift_table.txt)
 * [spb_temp.txt](./spb_temp.txt)
 * [straight_pbox.txt](./straight_pbox.txt)
 
   
---

## 🔎 Details of Codes

In this project, we are given a pair of plaintext and ciphartext, and an other cipher text which should be dycripted. The straight p-box in the encryption machine is defferent from the standard DES algorithm with just one round encryption, and we shall find out the straight p-box with the given pair of texts and key. To rich this goal, other parts of the DES algorithm are needed to be implemented. After that, we decrypt the other ciphertext and get its plaintext.


---
## 🤝 Collaborators
[Kian Majlessi](https://github.com/kianmajl) and [Audrina Ebrahimi](https://github.com/audrina-ebrahimi)
