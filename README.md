# swift-ci-image

This image contains Swift and Ruby.

You can run following command.

`swift test | xcpretty`

## Usage

1. ` $ docker pull kichiemon/swift-ci`
1. ` $ docker run -v ($pwd):/root/swift-project -it --rm kichiemon/swift-ci /bin/bash`
