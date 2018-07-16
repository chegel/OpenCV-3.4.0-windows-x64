# OpenCV

Add DLLs to Path
![title Windows Path](https://github.com/chegel/OpenCV-3.4.0-windows-x64/blob/master/images/Windows_Path.jpg)  
Add jar file to project lib folder  
Add Native Library Locations folder with DLLs  
![title IDEA libraries](https://github.com/chegel/OpenCV-3.4.0-windows-x64/blob/master/images/IDEA_libraries.jpg)  

In Java class load native library  

	static{
		System.loadLibrary(Core.NATIVE_LIBRARY_NAME); // load opencv_java
	}
	
