# macprosilentcool
Bash script to control cooling fans of MacBook Pro Laptops in Linux

In Linux fans of MacBook Pro Laptops often run at very high speed (over 3100 rpm) and they are very loud. 
Unfortunately at CPU temperatures below 75 degrees Celsius, cooling fans are more efficient at lower speeds (below 3100 rpm).

This script keeps CPU temperature in the range of 55-75 degrees Celsius by adjusting speed of fans at optimal rpm.
Fan speed is set above 3100 rpm only if CPU temperature goes above 75 degrees Celsius.

Superuser privilege is required to run.
