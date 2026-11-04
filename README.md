function printMessage(showUsage, message, showVersion) {
    console.log("Welcome To Line Counter");

    if (message) {
        console.log(message);
    }

    if (showVersion) {
        console.log("Version: 1.0.0");
    }

    if (showUsage) {
        console.log("Usage: node base.js <file1> <file2> ...");
    }
}