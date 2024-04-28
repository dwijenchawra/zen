# zen
local focus manager, powered by vision llms

## todo
- find a high resolution vision model (or find a way to train my own vision encoder + fuse onto llama3)
- implement python notification system with apple push notifications
- integrate into shortcuts and session pomodoro app

## Overview
Starting a "zen" session will allow you to set the focus to a string of choice. Zen periodically checks your screen on time intervals (focus changes / calendar events) and make sure you are on track.

## Requirements
- Computer running Ollama with a vision model (LLaVA 1.5/1.6 ideally)
- Python on the client