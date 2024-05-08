# Module 10
> M Azmy Arya Rizaldi M - 2206081704

#### Understanding How it Works
<img src="img/async-1.png">
The async function operates independently of the main execution flow, allowing the main program to proceed without waiting for the async function to finish. Thus, hey hey is printed outside the async function and immediately executed by the main program, while the async function awaits the future's result. This results in hey hey being printed before the async task is executed by the executor. Thats why the message hey hey gets printed before howdy!