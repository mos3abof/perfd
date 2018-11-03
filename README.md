# PerfD Project

A simple project to orchestrate perf commands on remote servers, from a central place.


# Components

## PerfD Server
- Orchestrates perf clients
- Collects perf client output
- Exposes API for querying information about perf clients, and/or perf dumps
- Manages perf output storage

## PerfD Client
- Keeps track of perf jobs to run on client
- Runs perf jobs (now, later, refularly)
- Sends output to server

## PerfD Dashboard 
- Visualize perf clients
- Visualize perf dumps
- Manage perf clients
- Manage perf dumps

## PerfD Alert
- Send notifications when dumps are ready


