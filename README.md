Tattler
=================
Performs tasks and keeps you updated on all the gory details.

What is it?
===========
Tattler is a tiny kernel suited to *run* *tasks* and keep you posted on their *progress*.
The core is big enough to be useful and small enough to be understood. The design philosophy is to hide
nothing from you while not overwhelming you with all the nitty gritty when you don't care for it.

The core can
 * define tasks
 * schedule tasks for running
 * track the progress on tasks
 * declare dependencies between tasks
 * be clever about execution order and failing fast
 
That's it!

The core is based on the whidely adopted Promise/A specification and the concept of streams build on top of
Promise/A whch makes it able to run asynchronous scenarious with ease.

What do I use it for?
=====================

Rant
====
