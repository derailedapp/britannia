# Britannia

Britannia is a Discoursy project made for asynchronous
scheduling and running of tasks.

## Why not use another TQ?

Since Discoursy will be using etcd instead of redis,
we found other tasks queues lacking the two things we required:

- asyncio support
- etcd support

So we decided to make Britannia as a way to make one with those features supported.
