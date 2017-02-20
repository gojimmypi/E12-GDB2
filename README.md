# E12-GDB2

This is a sample project that causes an error in Visual Studio when attempting to upload to ESP8266.

No ESP8266 is actually needed.

Open Project, Click on "Debug - Program and Start without Debugging". You should see this error:

>VisualGDB version: 5.2.14.1374
>------------------ System.NullReferenceException ------------------
>System.NullReferenceException: Object reference not set to an instance of an object.
>  at ESP8266DebugPackage.ESP8266StubDebugExtension.StubStartSequence.BuildSequence(String targetPath, Dictionary`2 bspDict, Dictionary`2 debugMethodConfig, LiveMemoryLineHandler lineHandler)   
>  at uc.k1(bz a, ICustomStartupSequenceBuilder b)   
>  at uc.l.c(bz a)   
>  at VisualGDB.Common_GUI.WPF.ItemizedProgressWindow.<>c__DisplayClass1_0`1.<RunAction>b__0()
