# Trading Engine (C++)

A simplified trading order matching engine built using C++.

## Features
- Handles buy and sell orders with price and quantity
- Supports partial order matching
- Uses STL priority_queue for efficient processing

## Concepts Used
- C++ (Structs, STL)
- Priority Queue (Max Heap & Min Heap)
- Custom Comparators
- Problem Solving

## How it Works
- Buy orders stored in max heap (highest price first)
- Sell orders stored in min heap (lowest price first)
- If buy price >= sell price → trade executes
- Supports partial matching of quantities
