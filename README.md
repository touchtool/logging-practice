## Logging Practice

1. Copy this repo to a public repository in your own Github account named `logging-practice`.
2. Perform the exercises described here <https://cpske.github.io/ISP/logging/logging-practice>.
3. Push your final code to Github.


## Exercise

What is lowest severity log message that is printed?     
             
    ```    
    logging.log(level, "custom log level message")
    ```

Which of your log messages are not printed?     
    ```
    logger.info("this is a info message")
    ```

How does the log message format change?      
    - the log format for ``simple_config`` has a datetime 
    that ```logging.basicConfig()``` doesn't has datetime.
    
How the output changes when use ``myconfig``.     
    - in Terminal show logging message `Logging to  <RootLogger root (Level 1000)>`.
    - It create `filename="website app"` for record the `logger.critical`.
    
Run the program a second time. Does the output append to the log file or overwrite the old log file?        
    - After run again nothing changing.
 
Do you see different messages for the root and foo loggers?
    - see name app from root to fake message in log format.