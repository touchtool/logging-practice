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