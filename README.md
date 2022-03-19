# FrontEnd-Notes

# Ways to Speed Up Website 
    Clean up the HTML document. Proper CSS placement. Proper JavaScript placement. 
    Optimize CSS performance.
    Reduce external HTTP requests.
    Minify CSS, JavaScript, and HTML.
    Enable prefetching.
    Increase speed with a CDN and caching.
    Compress your files.
    Optimize your images.
    Use a minimalistic framework
# Design Patterns

### Creational Patterns

    Abstract - FactoryCreates an instance of several families of classes
    Builder - Separates**object construction from its representation
    Factory Method - Creates an instance of several derived classes
    Prototype - A fully initialized instance to be copied or cloned
    Singleton - A class of which only a single instance can exist

### Structural Patterns 

    Adapter	- Match interfaces of different classes
    Bridge - Separates an object’s interface from its implementation
    Composite - A tree structure of simple and composite objects
    Decorator - Add responsibilities to objects dynamically
    Facade - A single class that represents an entire subsystem
    Flyweight - A fine-grained instance used for efficient sharing
    Proxy	- An object representing another object

### Behavioral Patterns

    Chain of Resp - A way of passing a request between a chain of objects
    Command - Encapsulate a command request as an object
    Interpreter- A way to include language elements in a program
    Iterator - Sequentially access the elements of a collection
    Mediator - Defines simplified communication between classes
    Memento - Capture and restore an object's internal state
    Observer - A way of notifying change to a number of classes
    State - Alter an object's behavior when its state changes
    Strategy - Encapsulates an algorithm inside a class
    Template - Method	Defer the exact steps of an algorithm to a subclass
    Visitor - Defines a new operation to a class without change

# Distributed Computing 

### Map Reduce
In distributed Computing, map is 
splitting all the inputs amongst many machines 
Reduce takes them all and combines them to get one result`,

### Distributed Caching 

An extension of the traditional concept of cache used 
in a single locale. A distributed cache may span multiple 
servers so that it can grow in size and in transactional 
capacity. It is mainly used to store application data 
residing in database and web session data.

### Load Balancing

Load balancing is a core networking solution 
used to distribute traffic across multiple servers in a 
server farm. Load balancers improve application availability
and responsiveness and prevent server overload.`,
Architectures

# DSAs   
## Understand the Space and Time Complexity of 
## different Data Structures and when to use them

## Algorithms

### DivideandConquer

### BFS

BFS stands for Breadth First Search is a 
vertex based technique for finding a shortest path in graph. 
It uses a Queue data structure which follows first in 
first out. In BFS, one vertex is selected at a time when 
it is visited and marked then its adjacent are visited 
and stored in the queue. It is slower than DFS
  
### DFS

DFS stands for Depth First Search is a edge based 
technique. It uses the Stack data structure, performs 
two stages, first visited vertices are pushed into stack 
and second if there is no vertices then visited vertices 
are popped.

**DFS Algorithms** 
*Inorder traversal*

Inorder (Left, Root, Right) : 4 2 5 1 3
Algorithm Inorder(tree)
   1. Traverse the left subtree, i.e., call Inorder(left-subtree)
   2. Visit the root.
   3. Traverse the right subtree, i.e., call Inorder(right-subtree) 

            var inorderTraversal = function(root) {
                let result = [];
                dfs(root);

                function dfs(root) {
                    if(root != null) {
                        dfs(root.left);
                        result.push(root.val);
                        dfs(root.right);
                    }
                }

                return result;
            };

*Uses of Inorder Traversals*
In the case of binary search trees (BST), Inorder traversal gives nodes in non-decreasing order. 
To get nodes of BST in non-increasing order, a variation of Inorder traversal where Inorder 
traversal s reversed can be used. 
Example: In order traversal for the above-given figure is 4 2 5 1 3.

*Preorder traversal*

Algorithm Preorder(tree)
   1. Visit the root.
   2. Traverse the left subtree, i.e., call Preorder(left-subtree)
   3. Traverse the right subtree, i.e., call Preorder(right-subtree) 


*Postorder traversal*

Algorithm Postorder(tree)
   1. Traverse the left subtree, i.e., call Postorder(left-subtree)
   2. Traverse the right subtree, i.e., call Postorder(right-subtree)
   3. Visit the root.

### BFSvDFS

DFS stands for Depth First Search is a edge based 
technique. It uses the Stack data structure, performs 
two stages, first visited vertices are pushed into stack 
and second if there is no vertices then visited vertices 
are popped  

## Random Terms 

### Protype

The prototype is an object that is associated with every 
functions and objects by default in JavaScript, where 
function's prototype property is accessible and modifiable 
and object's prototype property (aka attribute) is not visible.`

### Single Page Application

A web application or website that interacts 
with the user by dynamically rewriting the current web page 
with new data from the web server, instead of the default 
method of a web browser loading entire new pages. The goal 
is faster transitions that make the website 
feel more like a native app

### SPAvsTraditional

Traditional Web Pages are not dynamic and get all data for user 
each time the page loads. Also creates a new HTML page each time 
whereas SPAs replace the body each time

### DependencyInjection

In software engineering, dependency injection is a 
technique in which an object receives other objects that 
it depends on, called dependencies. Typically, the receiving 
object is called a client and the passed-in ('injected') 
object is called a service`, 

### HowMuchCodeCoverage

Acceptable is ~80%

### GarbageCollector

Garbage collection is the process in which programs try to free up 
memory space that is no longer used by objects.

### Screen-Readers 

What are screen readers and how do they work? A screen reader is a form 
of assistive technology (usually a software) used mostly (but not only) 
by people with vision impairments. Screen readers provide audio and braille 
output, and most of them also have visual indicators


# Common Amazon Questions On Site Interview 

### Behavioral 

https://leetcode.com/discuss/interview-experience/336727/Amazon-or-Front-End-Engineer-or-Seattle-or-July-2019-Reject/
https://leetcode.com/discuss/interview-experience/320613/Amazon-or-Front-End-Engineer-or-NYC-or-June-2019-Reject/

*Tell me about a time you had a tight deadline?
*Tell me about a time you went about the status quo?
*Tell me about a time you had a disagreement with a coworker?
*Possibly one or two more I can't remember
*Why Amazon?
*Tell me about a time you had a tight deadline?
*Tell me about a time you had a disagreement with a coworker?
*How did u handle a tough feedback
*Time when you went above and beyond your current role and contributed
*Time when you failed to deliver

*What is a Deadlock*
        In an operating system, a deadlock occurs when a process or thread 
        enters a waiting state because a requested system resource is held by 
        another waiting process,which in turn is waiting for another resource 
        held by another waiting process.
