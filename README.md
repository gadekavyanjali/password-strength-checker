# password-strength-checker
A  local user authentication system built with python sqlite3 . that evaluates password strength and securely stores user privacy passwords  in hash instead of plain text by using python's built in hashlib library.

key features:
-password strength evaluation: Analyzes local password to ensure they meet security criteria
-secure hashing: uses'hashlib'(eg SHA-256) to hash paswords securely before database storage
-local sqlite intrgration: lightweight,serverless local user authentication and storage
-privacy focused: no plain text passwords ever touch the database disk

prerequisities & installation
make sure you have python installation on your machine
1. Clone the repository
   bash
   git clone[https://https://github.com/gadekavyanjali/password-strength-checker.git](https://github.com/gadekavyanjali/password-strength-checker.git)
   cd password-strength-checker
   
