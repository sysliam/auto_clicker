# auto_clicker
Automatically clicks the screen based on X / Y axis declared in the code (variables $X / $Y), useful for keeping PCs awake when group policy doesn't allow you to change the time out.
The click is performed every 10 seconds, and is controlled using sleep -seconds X.

You don't need to change anything else, the sleep variable will also control how often the loop occurs as its essentially pausing the script for how many seconds you declare.
