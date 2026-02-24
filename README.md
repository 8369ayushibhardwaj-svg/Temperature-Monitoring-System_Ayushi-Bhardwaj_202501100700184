Problem Statement:
1. Build a Python code to display messages according to the temperature received from an assumed IoT system.
2. Accept max and min limit temperature.
3. Generate random values for temperature at every 2 second interval.
4. Compare with the limits to display appropriate value.


   Approach:
- Import required modules such as random and time.
- Take maximum and minimum temperature limits as user input.
- Use a loop to continuously generate random temperature values.
- Introduce a 2-second delay using time.sleep(2).
- Compare generated temperature with the limits:
  - If temperature exceeds maximum limit → Display "High Temperature Alert"
  - If temperature is below minimum limit → Display "Low Temperature Alert"
  - Otherwise → Display "Temperature is Normal"
  - 

Sample Output

Enter Minimum Temperature Limit: 20  
Enter Maximum Temperature Limit: 35  
Current Temperature: 28°C  
Temperature is Normal  
Current Temperature: 37°C  
High Temperature Alert!  
Current Temperature: 18°C  
Low Temperature Alert!
