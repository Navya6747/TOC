EXP NO 1. DFA for strings that start with 'a' and end with 'a'

Aim: To write a C program to simulate a Deterministic Finite Automata (DFA) that accepts strings starting with 'a' and ending with 'a'.

Algorithm: Read the input string. Check whether the first character is 'a'. Check whether the last character is 'a'. If both conditions are true, accept the string. Otherwise, reject the string.

Result: The DFA was successfully simulated.

EXP NO 2. NFA for strings that start with 0 and end with 1 Aim

To write a C program to simulate an NFA that accepts strings beginning with 0 and ending with 1.

Algorithm Read the string. Check first character. Check last character. If first character is 0 and last character is 1, accept. Otherwise reject.

Result The NFA simulation was completed successfully.

EXP NO 3. ε-Closure of an NFA

Aim To write a C program to find ε-closure of all states in an NFA.

Algorithm Enter number of states. Enter ε-transitions. For each state, display itself and all ε-reachable states.

Result The ε-closure of every state was obtained successfully.

EXP NO 4. Grammar S → 0A1 A → 0A | 1A | ε

Aim To check whether a string belongs to the grammar.

Algorithm Read string. Check first character is 0. Check last character is 1. Accept if true.

Result The string was checked successfully.

EXP NO 5. Grammar S → 0S0 | 1S1 | 0 | 1 | ε

Aim To check whether a string belongs to the grammar.

Algorithm Read string. Compare first and last characters. Continue inward. Accept if palindrome.

Result The palindrome string was verified successfully.

EXP NO 6. Grammar S → 0S0 | A A → 1A | ε

Aim To check whether a string belongs to the grammar.

Algorithm Count leading zeros. Count trailing zeros. Ensure equal number. Remaining symbols should be only 1's. Accept if true.

Result The grammar was verified successfully.

EXP NO 7. CFG S → 0S1 | ε

Aim To check whether a string belongs to the grammar.

Algorithm Count leading zeros. Count trailing ones. Numbers must be equal. No extra symbols allowed.

Result The CFG was verified successfully.

EXP NO 8. CFG S → A101A A → 0A | 1A | ε

Aim To check whether a string belongs to the grammar.

Algorithm Read string. Search for substring "101". Accept if found. Otherwise reject.

Result The string was successfully checked according to the given CFG.
