# 0x00. Personal data

## Tasks
### 0. Regex-ing
- Write a function called filter_datum that returns the log message obfuscated:

### 1. Log formatter
- Implement the format method to filter values in incoming log records using filter_datum. Values for fields in fields should be filtered.

### 2. Create logger
- Implement a get_logger function that takes no arguments and returns a logging.Logger object.

### 3. Connect to secure database
- Implement a get_db function that returns a connector to the database (mysql.connector.connection.MySQLConnection object).

### 4. Read and filter data
- Implement a main function that takes no arguments and returns nothing.

### 5. Encrypting passwords
- Implement a hash_password function that expects one string argument name password and returns a salted, hashed password, which is a byte string.

### 6. Check valid password
- Implement an is_valid function that expects 2 arguments and returns a boolean.
