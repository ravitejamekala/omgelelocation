# WebRTC IP Geolocation Interceptor

The WebRTC IP Geolocation Interceptor is a JavaScript script that intercepts ICE candidates in a WebRTC connection and retrieves the approximate location of the peer based on their IP address using the [ipgeolocation.io](https://ipgeolocation.io/) API. Please use this script responsibly and consider privacy and legal implications.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)


## Prerequisites

Before using this script, you need to obtain an API key from [ipgeolocation.io](https://ipgeolocation.io/). Replace `"mysampleapikey"` in the code with your actual API key.

## Getting Started

To use the WebRTC IP Geolocation Interceptor, follow these steps:

1. **Include the Script**: Include the JavaScript code in your web application where WebRTC connections are established.

2. **Replace API Key**: Replace `"mysampleapikey"` with your valid API key from [ipgeolocation.io](https://ipgeolocation.io/).

3. **Initialize WebRTC Connection**: Ensure that you have a WebRTC connection set up in your application.

4. **Intercept ICE Candidates**: The script will automatically intercept ICE candidates during the WebRTC connection process. When a server reflexive (srflx) candidate is encountered, it will fetch the location information for the peer's IP address and log it to the console.


**Disclaimer**: Please use this script responsibly and be aware of the legal and ethical implications of finding the location of individuals without their consent. Respect the privacy and safety of others when using this script.
