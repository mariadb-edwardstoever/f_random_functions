# f_random_functions
Database functions that can be used to create sample data.

F_RANDOM_ADJECTIVE
-- Returns a rich collection of random English adjectives.

F_RANDOM_ADVERB
-- Returns a rich collection of random English adverbs.

F_RANDOM_BOOLEAN
-- Returns a varchar(100) that represents a boolean such as y/n, yes/no, or 1/0.
-- First input, character for true.
-- Second input, character for false.
-- Third input, percentage of time it should return true. 100 is always true. 0 is never true.

F_RANDOM_BUSINESS_NAME
-- Returns a rich collection of random business names.

F_RANDOM_CITY
-- Returns a rich collection of random city names.

F_RANDOM_COUNTRY
-- Returns a rich collection of random country names. 
-- Input parameter 0: returns USA, Canada, or Mexico, 1: returns a real country, 2: returns a fantasy country

F_RANDOM_DATE
-- Returns a random date. Two input parameters indicate range from low days to high days. 
-- Use a negative number to indicate count of days ago (past). 
-- Use a positive number to indicate count of days from now (future). 
-- Use 0 to indicate today.

F_RANDOM_DATETIME
-- Returns a random datetime. Two input parameters indicate range from low minutes to high minutes.
-- Seconds are ranomized within the minute range.
-- Use a negative number to indicate count of minutes ago (past). 
-- Use a positive number to indicate count of minutes from now (future). 
-- Use 0 to indicate now.

F_RANDOM_DIGITS
-- Call this function with a mask in single-quotes. 
-- 000-00-0000 returns a random social security number.
-- (000) 000-0000 returns a random US-style telephone number. 
-- The mask can be up to 50 characters. 
-- Any non-numeric digit will be kept as is.

F_RANDOM_ECONOMIC_ACTIVITY
-- Returns a rich collection of random economic activities.

F_RANDOM_EMAIL
-- Returns a rich collection of random email addresses.

F_RANDOM_ENUM
-- Call this function with a comma-separated-values (csv) list as a single string. 
-- One of the values will be returned.

F_RANDOM_FIRST_NAME
-- Returns a rich collection of random first names.

F_RANDOM_FIRST_NAME2
-- Returns a rich collection of random first names, all different from F_RANDOM_FIRST_NAME. 
-- Can be used for middle names.

F_RANDOM_FLOAT
-- Returns a random float. The first two inputs indicate a range from low to high, negatives allowed. 
-- The third input is the scale or digits to the right of the decimal.

F_RANDOM_INTEGER
-- Returns a random integer from low to high inclusive. You can include negative numbers.

F_RANDOM_IPSUM
-- Returns a random string of Ipsum lorem text. 
-- Input maximum desired string length. Maximum output is between 5,000 and 6,000 characters.

F_RANDOM_LAST_NAME
-- Returns a rich collection of random last names.

F_RANDOM_LAST_NAME2
-- Returns a rich collection of random last names all different from F_RANDOM_LAST_NAME.

F_RANDOM_NOUN
-- Returns a rich collection of random nouns.

F_RANDOM_PRICE
-- Call this function with a mask in single-quotes. 
-- $00.00 returns a price such as $71.98. 
-- If random value is lower than $1, it will return with a leading zero such as $0.55.

F_RANDOM_PROFESSION
-- Returns a rich collection of random professions.

F_RANDOM_STATE
-- Returns a random state name. 
-- Input 0: returns a USA state. 
-- Input 1: returns Canada province.
-- Input 2: returns Mexico state.
-- Input 3: returns any of USA, Canada, or Mexico.
-- Input 4: returns a fantasy state.

F_RANDOM_STREET_ADDRESS
-- Returns a rich collection of random street addresses.

F_RANDOM_STREET_ADDRESS_2
-- Returns a random string to be used as the second line of a street address. 
-- Input parameter will indicate percent of calls that you want this function to return a zero length string. 
-- 0 will always return a string. 100 will always return a zero length string.

F_RANDOM_STRING
-- Returns a random string of alphabetic characters.
-- First input: length of string.
-- Second input: 0 for lowercase, 1 for uppercase.

F_RANDOM_USER_NAME
-- Returns a rich collection of user names.

F_RANDOM_VERB
-- Returns a rich collection of random English verbs.

F_RANDOM_WORD
-- Returns a rich collection of random English words.

F_UTF_RANDOM_FIRST_NAME
-- Returns a rich collection of random first names with mutli-byte characters for testing UTF scenarios.

F_UTF_RANDOM_STREET_ADDRESS
-- Returns a rich collection of random street addresses using multi-byte characters for testing UTF scenarios..

F_UTF_RANDOM_WORD
-- Returns a rich collection of random words with mutli-byte characters for testing UTF scenarios.
