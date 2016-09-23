# EmojiLogger
A custom Logger that uses emojis to represent log levels

### Usage

    🐛("This is a debug message")   
    💥("This is a warn message")
    💩("This is an error message")

>🐛 [DEBUG] This is a debug message  
💥 [WARN]  This is a warn message  
💩 [ERROR] This is an error message  

You can easily find these emojis by hitting `ctrl+cmd+space`. Once you use these they will be at the top of your list automatically. To find them the first time, hit `ctrl+cmd+space` and type "bug" to find "🐛", type "crash" to find "💥", and type "poop" to find "💩". I know what you're thinking... Why use the "crash" emoji for warn? Because the poop emoji is funnier. As in "Ahh shit! an error!"

You can also use:

    Log.debug("This is a debug message")
    Log.warn("This is a warn message")
    Log.error("This is an error message ")

>🐛 [DEBUG] This is a debug message  
💥 [WARN]  This is a warn message  
💩 [ERROR] This is an error message  

You can also set a custom level which allows you to easily filter your logs for your own debugging purposes.

    logLevel = .Custom("STEVE")
    Log.custom("This is a custom message for Steve")

>[STEVE] This is a custom message for Steve
