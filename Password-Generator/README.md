# Password Generator

This project is a Java Console Application designed to generate random passwords and perform password strength checks. It was built to help individuals create strong passwords and evaluate the strength of their existing ones.

## Introduction

During the semester break in my 5th semester, I decided to work on a project to reinforce my programming skills while exploring something practical. With security being a growing concern, I realized how important it is to have a strong password for online accounts, especially in the face of increasing cyber threats. This inspired me to create a password generator that not only generates random passwords but also evaluates their strength. After a few days of experimentation, I completed the project and was quite pleased with the outcome. 

## Functionalities

### 1. Generating a Password:

- The user is prompted to answer whether they want to include uppercase letters, lowercase letters, numbers, or symbols in the password.
- The user then inputs the desired length of the password.
- Based on these preferences, a custom alphabet is created by combining the selected character types.
- Random characters are chosen from this alphabet to generate a password according to the specified length.
- The generated password is then displayed in the console.

### 2. Checking a Password's Strength:

The strength of a password is assessed using the following criteria:
- The inclusion of uppercase letters.
- The inclusion of lowercase letters.
- The use of numbers.
- The use of symbols.
- A minimum password length of 8 characters (considered decent).
- A length of 16 characters or more (considered strong).

A score is calculated based on these factors, and the password is categorized as weak, medium, good, or great based on its strength.

### 3. Displaying Useful Information:

This feature provides valuable information on password security to help users improve their password hygiene. It advises against using the same password for multiple accounts, avoiding repetitive characters, steering clear of keyboard patterns, and other common security mistakes like using dictionary words or predictable letter/number sequences.

## Conclusion

Building this project allowed me to dive deeper into Java and apply object-oriented principles, all while addressing a real-world issue. It also served as a perfect way to spend my break productively, merging learning with something both practical and meaningful.
