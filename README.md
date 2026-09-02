# DarkCore Android Final v0.9

Complete Android project including Files Share and background reconnect support.

## GitHub
The `.github/workflows/android.yml` workflow is included. Push this folder's contents to the root of a GitHub repository.

## Features
- Cloudflare WSS connection
- Foreground connection service
- Reconnect after network loss
- Reconnect after task removal where Android permits it
- Boot reconnect attempt
- Camera/microphone/screen sharing with Android permissions
- User-approved folder sharing using Storage Access Framework
- Host can browse/download files from the approved folder

Android may restrict automatic service restart after Force Stop or OEM battery-management actions. Sensor access remains permission-controlled by Android.
