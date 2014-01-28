# cast-sender-tool-sample

This Google Cast Sender Tool application illustrates basic interaction with the Google Cast Chrome SDK. It is useful for testing Google Cast Receiver applications as the user can launch any receiver for which they have registered Cast devices and know the Application ID of the receiver they wish to launch. This sender application has been constructed to work with the cast-custom-receiver-sample in conjunction with the cast-support-media-server project.

## Dependencies
* cast-custom-receiver-sample
* (Optional) cast-support-media-server

## Setup Instructions
* You will need a Google Cast device such as a Chromecast to run this sample code
* Register your Cast device Developer Console ((http://cast.google.com/publish) to allow it to run this sample
* Setup the cast-custom-receiver-sample to act as the receiver
* Register a custom receiver application on the Cast Developers Console (http://cast.google.com/publish). The URL to use will be the IP address of the system you will run the receiver server from. If you run the server using the provided NodeJS server on your local machine, enter the ip-address of your computer with it's non local IP (eg. http://172.17.21.148:9999/sample_media_receiver.html). You will get an App ID when you finish registering your application.
* Setup the project dependencies (see below)
* Run the provided NodeJS server script using NodeJs or deploy to an existing server

## Project Setup
* Install NodeJS (http://nodejs.org/) for your platform
* In the root of this project execute
* $> npm install express
* $> node s3.js
* Receiver will be available on http://IP-Address:7777/web_sender_tool.html

## References and How to report bugs
* Cast APIs: http://developers.google.com/cast/docs
* Design Checklist (http://developers.google.com/cast/docs/design_checklist)
* If you find any issues, please open a bug here on GitHub

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE