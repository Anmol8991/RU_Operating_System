# CS518_User_Level_Thread_Library_and_Scheduler
## Introduction
The primary aim of the project was to create a thread library with a similar interface as that of
the pThread library. The first step was to flesh out the API skeletons provided to us, and by
doing so we could create, handle, synchronize and destroy worker threads just like pThreads.
The next step in creating this library was designing scheduling policies. We initially started with
a RoundRobin (RR) scheduler, and then moved on to define the two policies we wanted to
implement as per the write-up – Multilevel Feedback Queue (MLFQ) and Preemptive Shortest
Job First (PSJF).
