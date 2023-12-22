# communication test
## setup
```mermaid
graph LR
    USB --> b051
    b051 --> b016
```
## results
The connected PC was able to enumerate the bridge chip in b016 through the b051 connector.

# hub test
## setup
```mermaid
graph LR
    b051-->b094
    b094-->b120
    b094-->b002
```
Connected b051 to a computer and b120 to a mouse.

## results
The mouse worked.
