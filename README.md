I'm too busy right now, but someday when I finish writing this book and speaking and whatnot, I'm going to work through this list of projects. Feel free to start one without me or send a pull request to add to my list.

Contribute a telemetry interface to AllJoyn
--------------------

[AllJoyn][1] is an IoT protocol/framework that makes device-to-device communication as simple as object oriented programming. It would be great to make an interface for sending telemetry data.

* Receive PUBLISH messages from another node (probably a sensor or collection of sensors)
* Information to locate & connect to an [MQTT][2] broker.
 

Rust MQTT client
----------------

This is started [here](https://github.com/tkellogg/rust-mqtt). It's a [MQTT][2] client written in [Rust][3]. Needs a ton of work.


Contribute an OBD2 interface to AllJoyn
---------------------------------------

The device plugged into an OBD2 port from under the dashboard of a car should advertise this interface. Other devices (i.e. a smartphone, tablet, etc) can read all the information via [AllJoyn][1]. Maybe integrate with the telemetry interface.


 [1]: https://www.alljoyn.org/
 [2]: http://mqtt.org/
 [3]: http://www.rust-lang.org/
