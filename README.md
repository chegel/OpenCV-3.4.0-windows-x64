# OpenCV

Add jar file to project lib folder  
Add Native Library Locations folder with DLLs  
In Java class load native library  

	static{
		System.loadLibrary(Core.NATIVE_LIBRARY_NAME); // load opencv_java
	}
	
