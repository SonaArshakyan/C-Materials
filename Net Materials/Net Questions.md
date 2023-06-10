# Questions for the self-check: 

## Multithreading in .NET

➼ What is the purpose of threading in C#?

➼ What is the difference between thread and process?

➼ What is the difference between thread, thread pool and TPL? What is the preferred way to write multithreaded and parallel code?

➼ Describe a flow how exceptions are handled in threads?

➼ What is the difference between foreground and background threads?

➼ What is the difference between managed and unmanaged threads?

➼ What is spinning and how is it different from Blocking?

➼ What is Mutex? How is it different from other synchronization primitives?

➼ What ways /options to avoid deadlocks and race conditions and other threading issues do you know ?

➼ What is the difference between lock and monitor?

➼ How to write thread safe code?

➼ Name potential pitfalls in Task Parallelism?

➼ What is the difference between attached and detached Child Tasks?


## Async Programming

➼ What is the Async programming in C#?

➼ What are the key operators that are used for asynchronous operation? 

➼ If you mark a method with the async keyword, does this mean that the method is executed asynchronously?

➼ What Asynchronous programming patterns do you know?

➼ Can a method contain multiple “await” key operators?

➼ What types can be returned?


##  Message queues 

➼ What is a message queue? What do message queues store and transfer? 

➼ Describe the publisher/subscriber pattern. The difference between Pub/Sub and Observable patterns.

➼ What is Message Bus? How does it work? 

➼ What is the difference between message queue and web services? 

➼ Describe the difference between RabbitMQ and Kafka. Provide some use cases for each of them: in which scenarios you’ll use RabbitMQ, Kafka?

➼ How do messaging systems ensure reliable delivery and fault tolerance?

➼ What are some typical use cases for message queues in .NET applications?

➼ How do message queues handle message prioritization and ordering?

➼ What are some potential challenges and drawbacks of using message queues in .NET applications?


## Analyzing and profiling tools

➼ What profiling tools does Visual Studio provides?

➼ What typical performance issues could you mention? How to diagnose and prevent them?

➼ What .pdb files are and how are they used in debugging?

➼ What “Unmanaged resources” in .NET are?

➼ How do you understand Dispose pattern? How is it related to destructors (FinaliseFinalize)?

➼ How can you debug compiled applications? 

➼ Explain memory leaks in C#. What are some common causes, and how can you prevent them?

➼ What are weak references in C#? How can they be useful in memory management?

➼ How can you force garbage collection in C#? Is it recommended, and why or why not?

➼ How does the .NET runtime manage memory for large objects (greater than 85,000 bytes)?

➼ What are some best practices for improving string manipulation performance in C#?


##  LINQ, IQueryable

➼ What is the difference between IQueryable and IEnumerable interfaces? Provide some examples. 

➼ Describe IQueryProvider interface. What is it used for? 

➼ Analyze the task you worked on related to IQueryable topic. What is the role of Expressions for IQueryProvider? 

➼ Explain the difference between deferred (lazy) and immediate execution in LINQ. Provide examples of operators for each.

➼ What is Parallel LINQ (PLINQ), and when should you use it?


##   Expressions

➼ What is an expression tree?

➼ How can you create expression tree in C#?

➼ Are expression trees mutable?

➼ How will this expression be translated by compiler?


##  REST architecture

➼ Explain the difference between terms: REST and RESTful.

➼ What are the six constraints?

➼ Is HTTP the only protocol supported by REST?

➼ HTTP Request Methods (the difference) and HTTP Response codes. What is idempotency?

➼ What are the advantages of statelessness in RESTful services?

➼ What resource naming best practices are?

➼ What is Richardson Maturity Model?

➼ How can RESTful APIs be secured?

➼ How a RESTful API can be designed to support multiple data formats, such as JSON and XML.


