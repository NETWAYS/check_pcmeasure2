check_pcmeasure2
================

Plugin for pcmeasure (http://www.messpc.de)

### Requirements

* Perl libraries: `Nagios::Plugin`, `IO::Socket::INET`


### Usage

    check_pcmeasure2.pl -H <host> -S <sensor>[,<sensor] [-p <port>] [-w
    <threshold>] [-c <threshold>] [-v] [-V] [-R <rrd file>] [-T
    <sensortype>] [-t <timeout>] [-F <formatstring>] [-l <label>]

    Connects to the program pcmeasure or a ethernet messbox to ask for
    values of connected hardware sensors. pcmeasure is available as Linux or
    Windows program, the sensors are connected via serial or parallel port.
    On the standalone ethernet messbox the sensors are connected directly.
    There are different sensors available: temperature, humidity, voltage,
    smoke, motion, water and more. Please check www.messpc.de (german) or
    wwww.pcmeasure.com (english) for further informations.
