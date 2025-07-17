# 📝 Trie-Based Spell Checker

A C++ implementation of a spell checker using Trie (Prefix Tree) data structure. Suggests corrections for misspelled words and supports fast prefix lookups.

## 🚀 Features

- Insert and search words in O(n) time
- Suggest closest matches for invalid words
- Lightweight and easy-to-understand implementation
- Command-line based interface

## ⚙️ How It Works

- Words are stored in a Trie structure for efficient prefix-matching.
- When a word is not found, the program suggests corrections based on the prefix and edit distance.

## 📦 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/shailesh5751/SpellChecker.git
   cd SpellChecker

2. **Compile the program**

```bash
g++ spellchecker.cpp -o spellchecker
```

3. **Run it**
```bash
./spellchecker
```

## 🧪 Example
```bash
Enter word: appl
Did you mean: apple?
```

## 📁 File Structure
- spellchecker.cpp – main logic and Trie implementation

- dictionary.txt – word list (optional, can be customized)

## 🧑‍💻 Author
Shailesh More
📫 [LinkedIn](https://www.linkedin.com/in/shailesh-more) | [GitHub](https://github.com/shailesh5751)
