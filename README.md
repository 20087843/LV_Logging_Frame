# LV_Logging_Frame
This labview library is based on labview Actor Framework，which is used to log everywhere in labview program.



#### Platform and Requirement

windows 10

labview 2020



#### Use

1. create Log.xml with "Creat Setting.vi" in support folder.
2. call "Launch Log Man.vi" to initialize Logger Manager
3. call "Log.vi" to record your of your project



#### Extends Logger

this library provided Console and File Logger, you can extends "Generic Logger.lvclass" to implete costomized loggers.



#### Log.xml

1. Msg Pattern : there are only 4 pattern key words, 
   - $Time : record time info
   - $Level : log level
   - $Caller : the caller vi of the Log.vi
   - $Msg : msg content
2. Time Formart : reference labview help "Format Codes for the Time Format String "