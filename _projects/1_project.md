---
layout: page
title: RITA Copilot
description: An AI-driven Road Information and Travel Assistant.
img: 
importance: 1
category: fun
---

<div class="row">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/architecture.jpeg" title="System Architecture" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  System architecture of RITA Copilot.
</div>

## Project Overview
RITA Copilot is a comprehensive Road Information and Travel Assistant designed to enhance the driving experience through AI-driven technologies. It integrates voice recognition, natural language processing, and text-to-speech services to provide drivers with real-time assistance.

## Features
- **Voice Recognition:** Converts spoken commands into text using Azure's Speech SDK.
- **Natural Language Processing:** Classifies and responds to user queries with OpenAI's GPT-4 model.
- **Location Services:** Provides geolocation, searches for nearby places, and fetches directions via Google Maps APIs.
- **Vehicle Control:** Sets up the driver's seat based on predefined profiles through Kuksa Seat Control.
- **Text-to-Speech:** Converts textual responses into spoken words using Azure's Text to Speech service.

## Usage
Record an audio command using a microphone. The system processes the audio, converts it to text, and engages with the GPT-4 model for a categorized response. The copilot executes commands based on the identified category (e.g., welcome, route, service location) and converts textual responses to speech for playback.

## Dependencies
- Azure Speech SDK
- OpenAI GPT-4
- Google Maps APIs
- Kuksa Client
- PyAudio
- python-dotenv

## Links
- [GitHub Repository](https://github.com/DarioDiPalma-DDP/RITACopilot)
