AES-128-CBC Python Notebook
This repository contains a self-contained implementation of the AES-128 block cipher and its application in CBC (Cipher Block Chaining) mode, written entirely in Python without the use of any external libraries. The implementation is organized as a Jupyter Notebook and is suitable for learning, experimentation, and understanding the internals of AES encryption and decryption.

Table of Contents
Introduction

Features

File Structure

Usage

Assignment Structure

How It Works

Academic Integrity

License

Acknowledgments

Introduction
AES (Advanced Encryption Standard) is a widely used symmetric key encryption algorithm. This notebook demonstrates a full implementation of AES-128 (128-bit key) and its use in CBC mode. All cryptographic operations, including key expansion, SubBytes, ShiftRows, MixColumns, AddRoundKey, and CBC mode logic, are implemented from scratch for educational purposes.

Features
Pure Python implementation of AES-128 (no external libraries)

CBC mode encryption and decryption

Byte-level padding and unpadding

Detailed code with comments and explanations

Designed for learning and assignment use

File Structure
File Name	Description
AES-128-CBC.ipynb	Main Jupyter notebook with all code, explanations, and assignment questions
Usage
Open the Notebook:

Download or clone this repository.

Open AES-128-CBC.ipynb in Jupyter Notebook or Google Colab.

Run the Notebook:

Execute each cell in order. The notebook is designed to run end-to-end without errors.

Follow the instructions in the notebook for each section and question.

Assignment Completion:

Fill in your answers to short-answer questions in the provided markdown cells.

Implement the required Python functions in the designated code cells.

Do not import any external libraries; only built-in Python is allowed.

Assignment Structure
The notebook is structured as follows:

Section 0: Preparation

Introduction to AES and data representation

Helper functions for matrix/array conversions

Section 1: AES-128 Key Scheduling

Key expansion and round key generation

Section 2: AES-128 Encryption and Decryption

Implementation of encryption and decryption for a single block

Section 3: AES-128 with Block-Cipher Mode

Implementation of CBC mode, including padding and unpadding

Questions

14 questions in total: a mix of short-answer and implementation tasks

How It Works
AES-128 Implementation: All core AES operations are implemented manually, including S-Box lookups, key schedule, and block transformations.

CBC Mode: The notebook demonstrates how to use AES-128 in CBC mode to securely encrypt and decrypt multi-block messages.

Padding: The implementation includes byte-level padding to handle plaintexts that are not a multiple of the block size.

Testing: The notebook includes self-checks and assertions to verify correctness of each AES component.

Academic Integrity
This notebook is intended for individual use as part of a university assignment. Please ensure that all code and answers are your own, except where explicitly noted. Do not share your completed work with others or post it publicly until after grades are released.

License
This project is provided for educational purposes. If you wish to reuse or modify this code, please credit the original author and ensure compliance with your institution's academic policies.

Acknowledgments
AES algorithm details are based on standard cryptography references and course material.

Assignment structure inspired by university cryptography coursework.

Student Name: KSHITIJ SHUKLA
Student ID: 230583
Date: 10/06/25

Feel free to fork, clone, or use this notebook for your own cryptography learning!
