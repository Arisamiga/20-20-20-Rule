# <img width=50 style="vertical-align:middle" src="https://user-images.githubusercontent.com/64918822/210899404-babc36f6-4373-4a87-8ee8-4934b2242252.png"> &nbsp;20-20-20-Rule


> What's the 20-20-20 Rule?

Every 20 minutes spent using a screen; you should try to look away at something that is 20 feet away from you for a total of 20 seconds.


# Installation

```
Create a folder.
Open Command Prompt.
Type in: cd The path to your new folder. (Example: C:\Users\User\Desktop\New folder)
Press enter.
After that type in: git clone https://github.com/Arisamiga/20-20-20-Rule.git
Press enter.
When you see all Github files in your folder you installed the script file successfully.
```

* Note: This currently only works in Windows.

To Set the script to run every 20 minutes you can create a new task In Task Scheduler

# Steps to Creating a Task to run every 20 Minutes (Task Scheduler)

Open Task Scheduler

![image](https://user-images.githubusercontent.com/64918822/210897306-0ab5bb6f-56b7-48d2-9b73-72753acfaa78.png)

On the Right Side Press on "Create Task..."

![image](https://user-images.githubusercontent.com/64918822/210897638-0d77d7d1-56d8-4730-ab1e-7d48e555424d.png)

Write a Name and Description.

Then go to "Triggers" and Press "New..."

Make sure to have the following settings: 

![image](https://user-images.githubusercontent.com/64918822/211209316-ff174544-6603-4d3d-a3df-af86de8eeace.png)

* Note: You might not see an option on "Repeat task every:" for 20 minutes but you can click on the box and manually type "20 minutes"
* For the Trigger to work make sure you have set the Start Date at a date in the future like 3 minutes after your actual time should be fine.

Now When you have made your Triggers Go to "Actions"

Create the "New..." Button

Make sure it follows the following:

![image](https://user-images.githubusercontent.com/64918822/210898483-067af12d-73d3-48d1-b47a-f0b326e7bfdc.png)

* You can find the path to your Python exe by doing `where python` on your Command-Line.

* On the "Start in" you are gonna put the path to the folder where we have the .pyw File (Example: C:\Users\User\Desktop\New folder)

**After that you have successfully made a task where it will run every 20 minutes.**

# Notices

Huge thanks to the [Jason Chen (wontoncc)](https://github.com/wontoncc) for the balloon Tip Module for creating the notifications https://gist.github.com/wontoncc/1808234


## Code and bug reporting
You can open an issue at https://github.com/Arisamiga/20-20-20-Rule
