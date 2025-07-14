# Stock Portfolio Manager using Red-Black Tree (RBT) | Python + Tkinter

This project is a Stock Portfolio Manager developed in Python. It combines a user-friendly GUI built with Tkinter and an efficient Red-Black Tree (RBT) data structure to manage and display stock holdings effectively.

---

## Features

- Add new stocks by Ticker, Price, and Quantity  
- Search for stocks efficiently  
- Delete stocks from the portfolio  
- Display all stocks in ascending order using in-order traversal  
- Calculate and show total portfolio value  
- Graphical User Interface (GUI) built with Tkinter  
- Red-Black Tree ensures balanced and optimized operations

---

## How It Works

The application uses a Red-Black Tree to:
- Automatically maintain balance after insertions and deletions
- Perform operations like insert, delete, and search in O(log n) time
- Traverse the tree in order to present stocks sorted by ticker

Tkinter is used to build an intuitive GUI interface so users can interact with the system without needing to write code.

---

## File Description

- `project.ipynb`:  
  The main Jupyter Notebook containing:
  - Implementation of the `StockNode` class
  - Full Red-Black Tree logic (`insert`, `delete`, `search`, `display`)
  - Tkinter GUI for interactive stock management
  - Backend logic connected with frontend

---

## Technologies Used

| Technology     | Purpose                     |
|----------------|-----------------------------|
| Python 3       | Programming language         |
| Tkinter        | GUI development              |
| Red-Black Tree | Core data structure          |
| Jupyter Notebook | Interactive development environment |

---

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or any Python IDE

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-portfolio-manager.git
   cd stock-portfolio-manager
