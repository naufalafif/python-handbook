### Every Top Level Syntax like function, generator, context manager etc, alwasys have it's underline_function form

Asyncronous vs Concurrent vs Parallel vs async await

## Asyncronous
asynconous is the capability to run process without waiting other process to complete
ex : 
    process1() --> wait 10 second & print
    process2() 
in example ebove, process2 will be immdietly executed after process1 called, without have to wait for 10 seconds

## Concurrent
concurrent is the way code are executed. in normal way, all code are run in single thread, which means if u call 10 function that wait for 1 second, then 
u will spend 10 seconds to complete. using thread u can execute all 10 functon almost at the same time. cpu will jump from on function to another when current function are in idle. for example making http request or other i/o process

image example
https://techdifferences.com/wp-content/uploads/2017/12/Untitled.jpg

## Parallel
parallel in other hand, are running the code completely separated. 

## Async Await
async await are also different, async await are the way to achieve asyncronous. it also can execute code almost at the same time like concurrent using theads
but instead using multiple thread, async await use one thread(main) & another one thread to handle awaitable process.
async await use capability of programming language to pause/resume function process like generators.

# Asyncronous Programming 
Asynchronous programming is a type of parallel programming in which a unit of work is allowed to run separately from the primary application thread.