# Vending_machine_in-_verilog
Vending Machine FSM 🤖
This project is a simple Verilog implementation of a finite state machine (FSM) for a vending machine. It simulates the process of selecting a product, accepting payment, and dispensing the item along with any change. This was my very first project, designed to learn core digital logic and Verilog principles.

Features
State-based Logic: The vending machine's behavior is controlled by a 5-state FSM, handling everything from idling to dispensing products.

Product Selection: Supports three distinct products: Tea (cost: 20), Coffee (cost: 30), and Milk (cost: 10).

Flexible Payments: The system can handle initial payments and accepts additional money if the first payment is insufficient.

Change Calculation: Accurately calculates and returns the correct change after a successful transaction.

Files
vending_machine.v: The main Verilog module that contains the FSM logic.

vending_machine_tb.v: A comprehensive testbench for simulating and verifying the functionality of the vending_machine module.
