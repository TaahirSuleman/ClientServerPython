# Very Basic Python Server Implementation

This is a basic server implementation of storage and data transference. It uses the python socket module and employs hashing as a method of encryption in each data transfer. 

## Installation

One would only need to install python and they should be able to run this project.

```bash
pip install python
```

## Usage

Usage is really simple. Just make sure to run ```python server.py``` before running the client or else it will not work. The server has to be live to connect to it. When you run ```python MSLGRE001_client.py```, you need to input the IP of the server host machine as well as the predefined port number (currently 9999). You can then follow the prompts on the client instance to either download content or upload it. Files also are password protected by the uploader. Passwords are optional, and if someone wishes to share access to a file, they must share the password.

## A Note on Collaboration

This code was developed by GregoryMaselle, TaahirSuleman and prashanthPadiachy. server.py was coded by all 3, and each collaborator coded their own client.py files.
MSLGRE001_Client.py = GregoryMaselle, PDCPRA001Client.py = prashanthPadiachy, SLMTAA007_Client.py = TaahirSuleman.
