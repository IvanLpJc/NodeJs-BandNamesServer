# Band Names Server

Server made in NodeJs as part of the Udemy course [Flutter Avanzado: Lleva tu conocimiento al siguiente nivel](https://www.udemy.com/course/flutter-avanzado-fernando-herrera/) (Advanced Flutter: Bring your knowledge to the next level).

This server will be used as backend for the [Band Names App](https://github.com/IvanLpJc/Flutter-BandNamesApp/tree/main) developed in Flutter.

## Packages Used
- [dotenv](https://www.npmjs.com/package/dotenv): For environments configurations.
- [express](https://www.npmjs.com/package/express): Minimal and flexible Node.js web application framework.
- [nodemon](https://www.npmjs.com/package/nodemon): Monitor script for use during development of a Node.js app
- [socket.io](https://www.npmjs.com/package/socket.io): Library that enables low-latency, bidirectional and event-based communication between a client and a server
- [uuid](https://www.npmjs.com/package/uuid): For the creation of [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) UUIDs

## Models Used
- Band:
    - id: uuidV4 identifier.
    - name: Name of the band.
    - votes: Name of votes.
- Bands:
    - bands: List of bands.