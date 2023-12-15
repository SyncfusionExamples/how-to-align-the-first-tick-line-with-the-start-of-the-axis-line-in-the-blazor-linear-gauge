# Example of customizing the intersection of the tick line and bar pointer at the beginning in the Syncfusion Blazor Linear Gauge component

In this Blazor project, we created a sample to show how to calculate the position of the tick line and bar pointer properly at the beginning of the Linear Gauge.


In this smaple, we have calculated the position of the tick line and bar pointer element using JavaScript Interop method in a Blazor application. The position of the path in the tick line element can be calculated by the JavaScript code snippet using **customizePath**. This method can be invoked in the [Loaded](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.LinearGauge.LoadedEventArgs.html) event of the Linear Gauge. Now, the tick line and bar pointer are intersected properly at the beginning of the Linear Gauge.
