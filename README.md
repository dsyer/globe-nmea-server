# Globe NMEA Server

## How to configure OpenCPN

![OpenCPN](docs/nema_server.jpg)

Open Options, select Connections, Add Connection:

Network Connection
TCP
NMEA 0183
Address: localhost
DataPort: 3006

List position: 1
Receive Input on this Port ( ticked yes )

## Installation

Download latest release for your system:

https://github.com/marineverse/globe-nmea-server/releases 

## Usage Windows:

Get your [BOAT_UUID] from https://www.marineverse.com/globe

1. Right click on the file, ( Show More Options ) and create shortcut. 
2. Right click on the shortcut,  ( Show More Options ) and open Properties.
3. Modify "Target" by appending [BOAT_UUID] after globe-nmea-server.exe. It should be similar to: "globe-nmea-server.exe UUID-SDS-SDSSD-DSS".
4. Run the shortcut - the server should start ( You may need to select "Run anyway" and "Allow network connections" )


## Usage Mac:

Get your [BOAT_UUID] from https://www.marineverse.com/globe.

```
./globe-nmea-server-mac [BOAT_UUID]
```

## Usage Linux:

Get your [BOAT_UUID] from https://www.marineverse.com/globe.

```
./globe-nmea-server-linux [BOAT_UUID]
```
