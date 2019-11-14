fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios test
```
fastlane ios test
```
Runs all the tests
### ios beta
```
fastlane ios beta
```
Submit a new Beta Build to Apple TestFlight

This will also make sure the profile is up to date
### ios appstore
```
fastlane ios appstore
```
Deploy a new version to the App Store
### ios dev
```
fastlane ios dev
```
Submit a new Beta Build to Apple TestFlight

This will also make sure the profile is up to date
### ios certs
```
fastlane ios certs
```
Read only Sync AppStore and Development Certificates
### ios regen_certs
```
fastlane ios regen_certs
```
Sync AppStore and Development Certificates
### ios add_devices
```
fastlane ios add_devices
```
Add Devices
### ios create_app
```
fastlane ios create_app
```
Create app on Apple Developer and App Store Connect sites

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
