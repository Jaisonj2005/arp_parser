# Local ARP Cache Parser 🖧

A Python Network Operations utility designed to programmatically extract, parse, and analyze the host operating system's Address Resolution Protocol (ARP) table.

**Features:**
* Executes native OS-level network commands (`arp -a`) securely using Python's `subprocess` module.
* Employs Regular Expressions (`re`) to precisely extract valid IPv4 and MAC addresses from raw terminal output.
* Categorizes network neighbor allocations (Static, Dynamic, Broadcast) automatically.
* Visualizes the Layer 3 to Layer 2 mappings in a clean, sortable Tkinter Treeview data table.

*Built as Day 13 of a 30-Day Network Engineering & Security portfolio streak.*
