#Java Problem Set 1

1. The parameter weekday is true if it is a weekday, and the parameter vacation is true if we are on vacation. We sleep in if it is not a weekday or we're on vacation. Return true if we sleep in.
  ```
  sleepIn(false, false) → true
  sleepIn(true, false) → false
  sleepIn(false, true) → true
  
  public boolean sleepIn(boolean weekday, boolean vacation) {
    
  }
  ```

2. Given an int n, return the absolute difference between n and 21, except return double the absolute difference if n is over 21.
  ```
  diff21(19) → 2
  diff21(10) → 11
  diff21(21) → 0
  
  public int diff21(int n) {
    
  }
  ```

3. Given an int n, return true if it is within 10 of 100 or 200. Note: Math.abs(num) computes the absolute value of a number.
  ```
  nearHundred(93) → true
  nearHundred(90) → true
  nearHundred(89) → false
  
  public boolean nearHundred(int n) {
    
  }
  ```

4. Given a non-empty string and an int n, return a new string where the char at index n has been removed. The value of n will be a valid index of a char in the original string (i.e. n will be in the range 0..str.length()-1 inclusive).
  ```
  missingChar("kitten", 1) → "ktten"
  missingChar("kitten", 0) → "itten"
  missingChar("kitten", 4) → "kittn"
  
  public String missingChar(String str, int n) {
  
  }
  ```
  
5. Given a string, take the last char and return a new string with the last char added at the front and back, so "cat" yields "tcatt". The original string will be length 1 or more.
  ```
  backAround("cat") → "tcatt"
  backAround("Hello") → "oHelloo"
  backAround("a") → "aaa"
  
  public String backAround(String str) {
    
  }
  ```

