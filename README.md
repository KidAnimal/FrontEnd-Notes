# FrontEnd-Notes

# Ways to Speed Up Website 
    ```
    Clean up the HTML document. Proper CSS placement. Proper JavaScript placement. 
    Optimize CSS performance.
    Reduce external HTTP requests.
    Minify CSS, JavaScript, and HTML.
    Enable prefetching.
    Increase speed with a CDN and caching.
    Compress your files.
    Optimize your images.
    Use a minimalistic framework
    ```
# Design Patterns
    ```
    Singleton
    ```
# Map Reduce
```
In distributed Computing, map is 
splitting all the inputs amongst many machines 
Reduce takes them all and combines them to get one result`,
```
# Distributed Caching 
```
An extension of the traditional concept of cache used 
in a single locale. A distributed cache may span multiple 
servers so that it can grow in size and in transactional 
capacity. It is mainly used to store application data 
residing in database and web session data.
```
# Load Balancing
```
Load balancing is a core networking solution 
used to distribute traffic across multiple servers in a 
server farm. Load balancers improve application availability
and responsiveness and prevent server overload.`,
Architectures
```
# DSAs   
## Understand the Space and Time Complexity of 
## different Data Structures and when to use them

## Algorithms

### DivideandConquer

### BFS
```
BFS stands for Breadth First Search is a 
vertex based technique for finding a shortest path in graph. 
It uses a Queue data structure which follows first in 
first out. In BFS, one vertex is selected at a time when 
it is visited and marked then its adjacent are visited 
and stored in the queue. It is slower than DFS
```        
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

**Preorder traversal**

**Postorder traversal**

### BFSvDFS
```
DFS stands for Depth First Search is a edge based 
technique. It uses the Stack data structure, performs 
two stages, first visited vertices are pushed into stack 
and second if there is no vertices then visited vertices 
are popped  
```
### Traversals
```
```
# Random Shit 

## Protype
```
The prototype is an object that is associated with every 
functions and objects by default in JavaScript, where 
function's prototype property is accessible and modifiable 
and object's prototype property (aka attribute) is not visible.`
```
## Single Page Application
```
A web application or website that interacts 
with the user by dynamically rewriting the current web page 
with new data from the web server, instead of the default 
method of a web browser loading entire new pages. The goal 
is faster transitions that make the website 
feel more like a native app
```
## SPAvsTraditional
```
Traditional Web Pages are not dynamic and get all data for user 
each time the page loads. Also creates a new HTML page each time 
whereas SPAs replace the body each time`,   
DependencyInjection = `In software engineering, dependency injection is a 
technique in which an object receives other objects that 
it depends on, called dependencies. Typically, the receiving 
object is called a client and the passed-in ('injected') 
object is called a service`, 
```
## HowMuchCodeCoverage
```
Acceptable is ~80%
```
## GarbageCollector
```
Garbage collection is the process in which programs try to free up 
memory space that is no longer used by objects.
```
