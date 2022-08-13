# Palindrome Script

A script which detects the number of palindromic words.

## How to use

### Test a single word

```bash
$> echo 'noon' | ./palindrome
    1 noon 
```

### Using a file

```bash
$> cat text.txt | ./palindrome 
    4 noon
    2 anna
    1 wow
```

Words that are not palindromic will not return a response.
