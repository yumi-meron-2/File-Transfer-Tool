# Peer-to-Peer (P2P) File Transfer Application

## Overview
This Java-based Peer-to-Peer (P2P) file transfer application allows users to send and receive files over a network with a simple graphical user interface (GUI) built using Swing. It includes user authentication, secure password hashing, and logs file transfers in a MySQL database.

## Features
- **User Authentication**: Secure registration and login with password hashing using SHA-256.
- **File Transfer**: Send and receive files between peers over the network.
- **Transfer Logs**: Automatically log file transfer history including file name, size, direction (sent/received), and timestamp.
- **GUI Interface**: Easy-to-use graphical interface built with Swing.

## Technologies Used
- **Java**: Core programming language.
- **Swing**: GUI framework for building the application interface.
- **MySQL**: Relational database for storing user credentials and file transfer logs.
- **JDBC**: Java Database Connectivity API for interacting with MySQL.
- **SHA-256**: Secure hashing algorithm for password security.
- **Socket Programming**: For network communication between peers.

## Getting Started

### Prerequisites
- **Java Development Kit (JDK)**
- **MySQL Server**
- **MySQL JDBC Driver** (Ensure it is included in your project classpath)

### Database Setup
1. Start your MySQL server.
2. Create a database named `file_transfers`:
   ```sql
   CREATE DATABASE file_transfers;
