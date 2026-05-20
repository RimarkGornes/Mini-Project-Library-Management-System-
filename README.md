# Mini-Project-Library-Management-System-
This program is a command-line application designed to automate day-to-day library operations. It is structured around an object-oriented approach that maps data into distinct collections for books, members, and active rentals. 

Key Features & Workflow Mapping
Inventory & Registration Control:

Add Book (Choice 1): Captures the unique Book ID, title, and author, initializing the book's status as available.

Register Member (Choice 2): Captures profile details (ID, name, and email) to build a searchable registry of active borrowers.

Transaction Processing:

Borrow Book (Choice 3): Performs validation checks. If the book or member does not exist, or if the book is already checked out, it triggers explicit error paths. Otherwise, it toggles the availability status and creates a unique loan entry.

Return Book (Choice 4): Reverts the book state back to available and resolves the active loan log.

Data Reporting (Choices 5, 6, & 7):

Implements loop-traversal mechanisms that check for data records. If entries exist, it cycles through them sequentially to print formatted system headers and current status lists (e.g., distinguishing between "Available" and "Borrowed" items).

System Exit (Choice 8):

Gracefully breaks the runtime menu loop, terminates program processes, and returns control cleanly to the operating system.