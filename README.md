# Britannia

Britannia is a Discoursy project made for asynchronous
scheduling and running of jobs.

## Why not use another JQ?

Since Discoursy will be using etcd instead of redis,
we found other job queues lacking the two things we required:

- asyncio support
- etcd support

So we decided to make Britannia as a way to make one with those features supported.
