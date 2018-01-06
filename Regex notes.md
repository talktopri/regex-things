* These notes were taken while or after taking the _Learning Regular Expressions_ course found on [lynda.com](https://www.lynda.com/Regular-Expressions-tutorials/) and taught by [Kevin Skoglund](https://github.com/kevinskoglund).

----

## Regular Expressions

- Regular Expressions is a formal language interpreted by a regular expression process.
  - It is used for matching, searching, and replacing text.

----

### Metacharacters

Metacharacter | What does it do? | Example
------------- | ---------------- | -------
. | Matches any one character, except newline. | `/h.t/` matches "hat", "hot", and "hit". But it does not match "heat".
\ | Escapes the next character. Only for metacharacters Allows use of metacharacters as literal characters. | `/9\.00/` matches "9.00", but not "9500" or "9-00".