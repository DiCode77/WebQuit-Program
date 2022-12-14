# WebQuit-Program

WebQuit is a program for Web storage access, or access to your site.

The project is being developed, for commercial purposes, to make it possible to launch home storage on the local network, the project continued to develop further, the program's capabilities increased, it became possible to launch your site both on the local network and on the global one.

By functionality:
- The program is able to process dozens of requests, it is limited only by the power of the computer, as well as by the low speed of the Internet.
- It is possible to display notifications.
- Turn on the Status Tray.
- Enable access to the storage or site by password.
- There is a built-in WebView to quickly view the status of the server.
- Output of log information.
- For a local network, the program automatically selects an IP.
- Convenient and simple functionality.


---

How the program works:
 - On the local network:
   It is enough to generate an IP (on the main window, press "A"), then the correct IP address and port will be selected.
   
 - In the global network:
   To access the storage on the global network, you must specify the desired IP, usually the IP of your computer, and the correct port, it can be "8080" or some other. Important! you need an external IP that your telecommunications provider provides, and set up forwarding requests from an external IP to an internal IP.
   
---


Main window:

![WebQuit](./img/1.png)


Settings window, for password access:

![WebQuit](./img/3.png)


The password entry window:

![WebQuit](./img/4.png)

Status Tray for quick access to the program:

![WebQuit](./img/5.png)


---

- The software supports both x86_64 and arm64 architecture, two separate files will be available.
- Support for macOS 11 (Big Sur) - macOS 13 (Ventura).

---
To create a project, a library was taken [Mongoose](https://github.com/cesanta/mongoose)

The program is developed in C++
