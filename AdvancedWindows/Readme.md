# Readme - Code Samples for Chapter 40, Advanced Windows Apps

The sample code for this chapter contains this solution:

* ApplicationLifetime (saving navigation and session state)
* SharingData (share source and target)
* AppServices
    * BooksCacheModel (model data to share, .NET Standard class library)
    * BooksCacheService (Windows Runtime Component with IBackgroundTask)
    * BooksCacheProvider (app registering the background task)
    * BooksCacheClient (accessing App Services)
* CompiledBindingLifetime (Update, StopTracking)
* CompiledBindingMethods (using methods with compiled binding)
* PhasedBinding (x:Phase with compiled binding)
* TextSample (TextBlock, Bold, Hyperlink, Span, Run, RichTextBlock...)
* TextOverflow (RichTextBlock, RichTextBlockOverflow, AdaptiveTrigger)
* InkingSample (InkCanvas, InkToolbar)
* AutoSuggestSample (AutoSuggestBox)
* CameraSample (CameraCaptureUI, capability)
* MapSample (MapControl, SplitView, Geolocator)
* SensorSample (Accelerometer, Compass, Gyrometer, Inclinometer, LightSensor, OrientationSensor)
* RollingMarble (Accelerometer)

All the samples of this chapter need Windows 10 and Visual Studio 2017.

To build and run the Windows 10 samples, please install:

* Visual Studio 2017 Update 5 with the .NET Core workload **Universal Windows Platform Development**.

 
For code comments and issues please check [Professional C#'s GitHub Repository](https://github.com/ProfessionalCSharp/ProfessionalCSharp7)

Please check my blog [csharp.christiannagel.com](https://csharp.christiannagel.com "csharp.christiannagel.com") for additional information for topics covered in the book.

Thank you!