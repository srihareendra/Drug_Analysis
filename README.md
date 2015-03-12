Rquirements and Steps to bee followed
1.You require eclipse ide installed.

2.Fork the project.Import the project into eclipse work space(You need have android ADT plugin installed you can find it here http://developer.android.com/tools/sdk/eclipse-adt.html)

3.Download and install android NDK. Update the path in system variables and also in eclipse eclipse--.windows-->preferences-->android-->NDK

4.Fork tess-two project from here https://github.com/rmtheis/tess-two

5. Open CMD or shell go to the folder containing tess-two and type ndk-build.

6.import the tess-two project into eclipse and change it to Library project(project-->properties-->android-->Is Library tick)

7.Import the Drug analysis into your workspace(containing tess-two) and add tess-two as library( project-->properties-->android-->add-->add tess two)

8.Run it .It works


I have included open cv snippets as comments if you want further enchance the code you can uncomment them and for full details and explanation you can visit https://c3.csc.com/groups/innovation-labs/blog/2015/01/12/drug-recommendation-application-in-android-and-python-using-ocr  
