# Town Data Management System

## Overview

This C program implements a data management system for towns using two main data structures:

- **AVL Tree**: For efficient and balanced storage of towns sorted by their names.
- **Hash Table**: For fast insertion, search, and deletion using the first 5 characters of the town name as the key.

Each town record includes:
- District name
- Town name
- Population
- Elevation
- Municipality status (`yes`/`no`)

---

## Features

### AVL Tree
- **Insert** a new town.
- **Delete** a town by name.
- **Traverse** in-order to print towns alphabetically.
- **List towns** with a population greater than a specified value.
- **List towns** with or without a municipality.
- **Find and update** town information.
- **Save** the tree data to a file.

### Hash Table
- **Insert** a town using the first 5 characters of the town name.
- **Search** for a town with collision handling (linear probing).
- **Delete** a town from the table.
- **Print** the entire hash table.
- **Calculate the load factor** of the table.
- **Save** hash table data to a file.

