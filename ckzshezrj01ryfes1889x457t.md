# Getting Started With Shell Scripting(Shell Programming)

## What is a Shell?

A shell is a command line tool in Linux/Unix operating systems. It processes the command entered by the user and interprets into machine-readable binary form that can be understood by the **Kernel** to carry out the process.

---

## What is Kernel?

> The kernel is a computer program at the core of a computer's **operating system** and generally has complete control over everything in the system. It is the portion of the operating system code that is always resident in memory, and facilitates interactions between hardware and software components.
- Source: **Wikipedia**

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645185232127/gLBXVShdA.png)

This picture is taken from *GeeksForGeeks* website.

---

## What is a Shell Script?

> A shell script is a computer program designed to be run by the Unix shell, a command-line interpreter.
- Source: **Wikipedia**

We write shell script with the help of a special program called **terminal** of the Operating System. Terminal looks similar to the Command Prompt or Windows Powershell of Windows Operating System.

---
## Types of Shell

There are various types of shell in Linux.
Some of them are as follows - 
1. Bourne Shell
2. C Shell 
3. Korn Shell
4. Bourne Again Shell

---
## Shell Prompt

$ sign in the terminal is known as the **Shell Prompt**.

---

## Using Shell in Windows

For Windows users, you can do any of the following - 
1. Set up your computer for dual boot - containing both Windows and Ubuntu together.
2. Install the [virtual box](https://www.virtualbox.org/wiki/Downloads) in your computer containing the Linux OS.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645189129153/hizYi9MtK.png)
3. Use Windows Subsystem for Linux( [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)) by installing it.
4. Otherwise, you can use a Browser extension named [OnWorks](https://www.onworks.net/applications/web-extensions/ubuntu-online-extension-for-chrome-and-firefox) to run Ubuntu or Kali Linux online.
---
### OnWorks Extension

OnWorks extension works on Firefox and Chrome Browsers. It acts as an emulator for the windows system creating the ISO image of the chosen OS to run it online. 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645186571970/UgjunzjP2.png)

- **Benefit** of using this extension is that you can use any OS you like to run online and all are free to use. Also, you can save your work in your Google Drive.
- **Disadvantage** of using it is that if you leave the tab inactive for more than 10 minutes, then you have to run the OS again as it logs you out from the session automatically. So, sometimes you might get irritated.

---

## Writing Our First Shell Script

1. Search for terminal in the search bar
2. Open your terminal
3. Type `gedit <filename>.sh` and then hit Enter. 

For example:- 
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645190453984/tW27_sjxX.png)

4. Then you'll see a text editor opens up with the file name like this -
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645190596412/PTyUvvbhY.png)
5. Now, we're are ready to write our code.
```bash
echo "Hello World"
```
6. Now save the file and open a new terminal.
7. Type `bash <filename>.sh`. Here, `bash hello.sh`.
8. Now hit Enter to see the output. 
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645190817469/otwgI9Zy7.png)

---
### Congratulations 🎉 You have written your first shell script program.

### You can also watch this [video](https://www.youtube.com/playlist?list=PLEvX_vrDiWMNlvp8NW_IK3kqLK-cIhY53) for clarity.
---

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊
