# AyroVoice Interview Studio

**A browser-based voice interview demo built around an actual conversation.**

## The problem

The original brief was specific: a German-speaking chef recruiter, three qualification questions, and enough patience to let the candidate answer.

A voice agent that talks over the person it is interviewing rather defeats the purpose. The demo later grew beyond chefs so clients and employers could try the same interaction for other roles.

## The solution

A configurable browser interview studio with live speech-to-speech interaction, call controls, transcript/activity feedback, and structured interview outcomes.

## What it does

- Configurable role and candidate context.
- English/German interview flows.
- One-question-at-a-time conversation and interruption handling.
- Start, end, and mute controls with connection/error feedback.
- Transcript/activity and structured outcome displays.
- Password-gated session creation with the permanent API key kept server-side.

## Engineering highlights

A Node server creates the session, while browser WebRTC handles the live microphone conversation. Tool-call events update local action/result displays. Cleanup closes the microphone tracks and connection when the session ends.

## Technology

Node.js, Express, browser JavaScript, WebRTC, OpenAI Realtime.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
