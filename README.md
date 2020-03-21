## Debugger

Real-time code inspection
Pause, step, and watch

## Basic concepts

1. Breakpoint : a place that tell the debugger to stop the execution of code to do something
2. Stepping :
   A. Step Over : execute the line you are on and step to the next one in the file you
   are in and step to the next
   B. Step Into : take you into the next function call on the line you're executing
   C. Step Out : take you from where you're and step you out from the function you're
   currently executing
3. Watch : taking a look at a particular variable or an expression to see over time
4. Call Stack : This is the series of functions that were called to get to the place where we
   have stopped and are actually looking around and a call stack is made up of frames
5. IDE : a piece of software that collects important things that a programmer needs usually
   includes a powerful text editor and a debugger, among other features

## Debugging AJAX

### There are 2 security issues

1. Same-origin policy
   This means that all of your assets and data need to come from the same place ( the same server )
2. CORS ( Cross-Origin Resource Sharing)
   The access control for sharing data across domains

### Solutions

1. Local web server
2. Chrome: disable web security
