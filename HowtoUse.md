
```
ProcessTimeHelper.clear();
```
  1. Get code execution time.
```
ProcessTimeHelper.start();
// This is your code here.
ProcessTimeHelper.end();
ProcessTimeHelper.getProcessTime();
```
  1. Or, Show
```
ProcessTimeHelper.displayProcessTime();
//...if you want to do more process and get average and total time, repeat above.

//then, show average time.
ProcessTimeHelper.displayAverageTime();
//or, show total time.
ProcessTimeHelper.displayTotalTime();
```