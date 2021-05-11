# rCDocs
The rC Programming Language Documentation
rC is a high-level intepreted programming language based on top of .NET created by Rodrigo Cabaco;
The source code is available at https://www.github.com/RodrigoCabaco/rC;

Here's an example of an rC Program:

```
function main();{
    Write "Hello There!"
}main;

newln
exit()
```
Output:
Hello There!

# - Installing

Step 1 - Installing .NET Dependencies:
    Since rC is built with C#, you will need dotnet runtime (for running) and dotnet sdk (for building) installed on your machine;
    - If you're on windows just google "how to install dotnet core sdk and runtime";
    - If you're on linux mono, mono-complete and monodevelop should do the job!
    Note: if you are running a debian distribution, just go ahead and download the requirements.sh file from rC's source code and run it!


Step 2 - Installation:
    Once dotnet is installed, download the latest binary from the rC Repository;
        If you're on linux, place it inside /usr/bin/ and add the following line to your .zshrc/.bashrc:
            "alias rC="mono /usr/bin/rC"
        If you're on windows, place it inside C:\Users\Username\

Installation is complete, to test if rC is installed just open cmd/shell and type: "rC";

# - Creating a Project

To Create a project just type "rC" in cmd or shell and then type "create_project project_name"
If you get a greenish message saying "Project created Successfully!" just exit by pressing Ctrl+C;

Then type cd "project_name" and "code ." if you have vscode installed, or just open it in your favorite text editor;

# - Configuring vscode

Since the rC Syntax is quite like python, just configure vscode to use python Syntax Highlighting on .rcode file extension (and disable pylinter)
If you want intellisense to work, just download .rC_Autocomplete from https://www.github.com/RodrigoCabaco/rC_Autocomplete and place it in your project's directory

To run your project just go inside it and type "rC Main.rcode"
Great, now everything's good to go and you can just go through the documentation to learn more!
