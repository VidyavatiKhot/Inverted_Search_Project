# Inverted Search in C

A lightweight and efficient application that builds an Inverted Index from multiple text files.
This project is developed using C programming, demonstrating the practical use of hashing, linked lists, dynamic memory allocation, and file handling.

## **Objective**
The main objective is to create a fast and searchable index of words from multiple files.
The system maps each word to:
- the files in which it appears
- and how many times it appears in each file
This replicates the core behavior of search engines.

## **Features**
- Validate input files (.txt format, duplicates, empty checks)
- Build an inverted index using hashing (A–Z)
- Store words, file names, and occurrence counts using linked lists
- Display the complete database in a structured format
- Search for any word across all files
- Save the database to a backup file
- Restore (update) the database from backup
- Strict rule: Only one Create OR one Update allowed (mutually exclusive operations)

## **Technologies Used**
- C Programming
- Hash Table
- Linked Lists
- File Handling
- Dynamic Memory Allocation
- Modular Functions

## **Conclusion**
The Inverted Search Engine provides a clear and efficient way to index and search text-based data.
It demonstrates key concepts in C such as hashing, dynamic structures, file parsing, modular programming, and data management.
This project reflects how real-world search engines build and maintain keyword–document mappings.

## **Future Scope**
- Implement better hashing for uniform distribution
- Add stop-word removal and word stemming
- Introduce ranking algorithms (TF–IDF) for smarter search
- Support multi-threaded file processing
- Integrate with SQL/NoSQL databases
- Add a GUI or web-based front-end
- Real-time auto-update when files change

## How to RUN
make clean && make
./inverted.out file1.txt file2.txt ...
