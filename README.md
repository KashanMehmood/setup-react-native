# setup-react-native
This is the setup instruction for react native.


1. Downlaod Nodejs
2. Download Android Studio
   1. Select standard
   2. Set Envirnoment Variable in both envirnoment variable path section
      1. New >
         Variable Name: ANDROID_HOME
         Variable Path: C:\Users\Kashan\AppData\Local\Android\Sdk 

      2. Add Platform Tools
         Select Path > Edit > Paste
         C:\Users\Kashan\AppData\Local\Android\Sdk\platform-tools

      3. Tools > Avd Manager
         1. Create a virtual device

3. Download jdk v12
	jdk-12.0.2_windows-x64_bin.exe
   https://www.oracle.com/java/technologies/javase/jdk12-archive-downloads.html

   Check Envirnoment Variable
      1. open cmd
      2. javac
   
   Set Envirnoment Variable
      1. Copy Path and paste in both envirnoment variable path section
         C:\Program Files\Java\jdk-12.0.2\bin

4. Downlaod Python 2
      1. Windows x86-64 MSI installer
         https://www.python.org/downloads/release/python-2717/

5. Open cms as Administrator
   1. Run command
      npm install –g react-native-cli

6. Setup first react native project 
   1. npx react-native init <ProjectName>