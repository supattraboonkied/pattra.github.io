# Test Case
test Case ID : Login-1	
Test Senario : Authentication Limits 
Third time fail login 3 minute delay 
prerequisition : login fail 2 time	 
test condition : login in Third time fail 3 minute delay 

| No |     Action    |    Inputs   | Expected Output  |   Actual output   | 
| -- | ------------- | ----------- | ---------------- | ----------------- |
| 1 | login#1 | username + Password | username or password fail | username or password fail | |
| 2 | login#2 | username + Password | username or password fail | username or password fail | |
| 3 | login#3 | username + Password | username or password fail and delay refresh page 3  minute | username or password fail and delay refresh page 3  minute | |
| 4 | login#4 | username + Password | username or password fail and delay refresh page 3  minute | username or password fail | | |



Members 
Nantawan Sanpukdee 
Supattra Boonkied 