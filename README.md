# ssh-part2
- Introduce a Man-in-the-Middle as there is no checking if the server is who it claims to be
- Client uses the wrong IP, MITM uses the correct IP to connect to the real server
- MITM receives the symmetric key and is able to read the file
- MITM sends a 'bad' file to the real server
