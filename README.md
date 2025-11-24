# Multithreading-Java-Project
Sample Output:
Download Manager Started

Starting download: File1.pdf on Thread-1
Starting download: File2.mp4 on Thread-2
Starting download: File3.zip on Thread-3
Main thread is free to do other tasks...

Downloading File1.pdf ... 20% completed
Downloading File2.mp4 ... 20% completed
Downloading File3.zip ... 20% completed
...
Download completed: File1.pdf on Thread-1
Download completed: File2.mp4 on Thread-2
Download completed: File3.zip on Thread-3

How to Run:
1. Save both classes (FileDownloader and project) in your project directory.
2. Compile the project using a Java compiler, e.g.:
   javac project.java
3. Run the project:
   java project

Learning Objectives:
- Understand the basics of Java multithreading using the Runnable interface and Thread class.
- Observe how simultaneous downloads are managed without waiting for one to finish before starting the next.
- See how the main application remains responsive while concurrent tasks run in parallel.
