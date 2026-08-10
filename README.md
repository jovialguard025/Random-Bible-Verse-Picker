# 📖 Random Bible Verse Picker

A simple Python program that picks a random Bible verse reference (Book, Chapter, Verse) from the Old and New Testament.  
This ensures that the output is always a valid reference by using a structured dictionary of books, chapters, and verse counts.

 ✨ Features
- Randomly selects a **book** from all 66 books of the Bible.
- Randomly selects a **chapter** within that book.
- Randomly selects a **verse** within that chapter.
- Guarantees valid references (no impossible verses like *Hosea 4:146*).
- Lightweight and easy to extend.


🛠️ How It Works
1. A dictionary (`bible_structure`) stores each book of the Bible.  
2. Each book maps to its chapters, and each chapter maps to the number of verses.  
   Example:
   ```python
   bible_structure = {
       "Genesis": {1: 31, 2: 25, 3: 24, ...},
       "John": {1: 51, 2: 25, 3: 36, ...},
       "Psalms": {1: 6, 2: 12, 3: 8, ...}
   }

Random-Bible-Verse-Picker/
│
├── Bible_Verse_Picker.py   # Main script
└── README.md               # Documentation
