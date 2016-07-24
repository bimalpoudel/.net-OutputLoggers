.DLL Library to Log Ouputs to a File

## Usage

```
FileLogger fl = new FileLogger();
fl.writeLog("A log has been initiated.");
```

## Customization

```
FileLogger fl = new FileLogger();
fl.writeToPath(@"d:");
fl.writeToFile(@"custom-log.txt");
fl.writeLog("A log has been initiated.");
```
