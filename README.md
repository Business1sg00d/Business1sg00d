I'm in the process of learning the dense field of cybersecurity. Through that process I discovered coding and thus how it can be a tool to
augment learning.

I have been writing a script using nmap.
I have encountered an error that I have been unsuccessful in rectifying.
My hope is that someone here can help with fixing this issue before I continue with its development.

The issue resides within the functions 'scanprogress' and 'scanprogressVersion'.
I recieve an error 'Segmentation Fault' on the line of code where the function is created.
This occurs anytime I run the script where the while loop condition within the 
function becomes false. At least that's what it looks like to me.
I believe this has something to do with the older version 7.92; newer is 7.93
