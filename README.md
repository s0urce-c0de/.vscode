# Visual Studio Code `.vscode` templates

VSCode .vscode folders to copy into your project for easy development.
For example, you have a django application, so download the [tarball](https://github.com/s0urce-c0de/.vscode/archive/refs/heads/main.tar.gz)
or [zip file](https://github.com/s0urce-c0de/.vscode/archive/refs/heads/main.zip) and extract
or clone via `git clone https://github.com/s0urce-c0de/.vscode.git` or `gh repo clone s0urce-c0de/.vscode`.
Then copy the folder (django in out case), to your project and rename it to .vscode and enjoy :)
To copy do 
```shell
cd "/path/to/your/repository/clone/"
cp -r django "/path/to/vscode/project"
cd "/path/to/vscode/project"
mv --backup=t django .vscode
```
on UNIX based systems (MacOS, Linux, Minix, etc.). On Windows do 
```cmd
cd "C:\path\to\your\repository\clone\"
xcopy /E /I django "C:\path\to\vscode\project\django-vscode"
cd "C:\path\to\vscode\project"
move /Y django-vscode .vscode
```
