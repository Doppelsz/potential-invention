# Project Goal Design Checklist Example

Purpose – What problem does your network solve?
Example: “Allow multiple clients to communicate reliably via proxies to a central server.”

Scope – Define boundaries.
Example: “Client, proxy, and server in C; no GUI; TCP only.”

Performance Targets – Speed, concurrency, or load expectations.
Example: “Handle 50 simultaneous clients per proxy.”

Security – How safe should it be?
Example: “Hardened C code, prevent crashes and memory bugs.”

Scalability – Can it grow?
Example: “Add multiple proxies and servers later without redesign.”

Redundancy / Reliability – Handle failures.
Example: “Clients can switch to another proxy if one fails.”

Maintainability – Easy to update and debug.
Example: “Separate modules (client.c, proxy.c, server.c) and clear Makefile.”

Testability – Can you validate it works?
Example: “Echo test messages through proxy to server and back.”

Deliverable – What constitutes “done”?
Example: “Client sends message → proxy forwards → server responds → client receives response correctly.”
