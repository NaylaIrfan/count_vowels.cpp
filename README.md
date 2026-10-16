# count_vowels.cpp

# Count Vowels in a String (C++)

A beginner-friendly C++ program that counts the number of vowels in a string entered by the user.

## About

The program reads a full line of text and checks each character. If the character is a vowel (`a`, `e`, `i`, `o`, `u`, in small or capital letters), it adds 1 to the count. At the end, it prints the total number of vowels.

## Example

```
Enter a string: Hello World
Number of vowels: 3
```

```
Enter a string: Programming in C++
Number of vowels: 4
```

## How It Works

1. Read the full line using `getline(cin, str)`.
2. Set a counter `count` to 0.
3. Go through each character one by one.
4. If the character is a vowel, increase `count` by 1.
5. Print the final count.

## Things to Note

- Both uppercase and lowercase vowels are counted.
- Spaces, digits and symbols are ignored.
- Only `a`, `e`, `i`, `o`, `u` are treated as vowels.

## Concepts Used

- Strings (`string`)
- Input and output (`cin`, `cout`, `getline`)
- `for` loop
- `if` condition with `||` (OR) operator
- Counter variable
- `tolower()` function (in the shorter version)

## How to Run

Make sure a C++ compiler such as `g++` is installed.

```bash
# Compile
g++ count_vowels.cpp -o count_vowels

# Run (Linux / macOS)
./count_vowels

# Run (Windows)
count_vowels.exe
```

## Project Structure

```
count-vowels-cpp/
├── README.md
└── count_vowels.cpp
```

## Author

NAYLA IRFAN 
B.Tech CSE

## License

This project is free to use for learning purposes.
