 Step 1: Install Java (JDK)

1️⃣ Go to the Oracle JDK Download Page.
2️⃣ Download the Windows x64 Installer for the latest LTS version.
3️⃣ Run the installer and follow the instructions to complete the installation.

✅ Check Installation:
Open Command Prompt and type:

java --version

Step 2: Create a Folder to Save Your Java Program

📁 Create a folder in any drive (for example, D: drive) and name it something like:

D:\javaprogram

Step 3: Write the Program

✏️ Open Notepad (or any text editor) and write the following code:

public class testjava {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}


⚠️ Important: The file name must match the class name exactly.
So save the file as:

testjava.java

Step 4: Open Command Prompt and Navigate to the Folder

📂 In Command Prompt, type:

cd D:\javaprogram

Step 5: Compile the Program

💻 Compile your Java file using the javac command:

javac testjava.java


If there are no errors, it will create a testjava.class file.

Step 6: Run the Program

▶️ Run your compiled Java program using:

java testjava


✅ Output:

Hello, World!
