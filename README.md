
# SA:MP DDOS v1.0.0

SA:MP DDoS v1.0.0 is a tool for performing Denial of Service (DoS) attacks on SA:MP (San Andreas Multiplayer) servers using the UDP protocol. This tool allows sending packets with various payloads to test the server's resilience against DoS attacks.

## Features

- Send UDP packets with predefined payloads.
- Support various payloads to test the server on specific ports.
- Use threading for simultaneous packet delivery.

## Prerequisites

- Python 2.7 or Python 3.x
- Modules `socket`, `sys`, `threading`, `random`, `time`, `os`, and `argparse` (all are built-in Python modules)

## Installation

1. Ensure Python is installed on your system.
2. Download or clone this repository.

## Usage

1. Run the script with the following arguments:

   ```sh
   python3 saddos.py -s <SERVER_IP> -p <PORT> -t <THREADS>
   ```

   - `-s` or `--server`: The IP address of the target server.
   - `-p` or `--port`: The port number of the target server.
   - `-t` or `--threads`: The number of threads to be used for sending packets.

2. Example command to run the script:

   ```bash
   python3 saddos.py -s 192.168.1.1 -p 7777 -t 10
   ```

   The above command will send packets to the server with IP `192.168.1.1` on port `7777` using 10 threads.

3. To stop the attack, type `stop` when prompted in the terminal and press Enter, or press `Ctrl + C` to terminate the process.

## Disclaimer

This tool is provided for educational and security testing purposes only. Use of this tool for malicious or illegal purposes is prohibited and may violate the law. The developer of this tool is not responsible for unauthorized use or damage caused by the use of this tool.

## Contact

For questions or feedback, you can contact the developer at [@Fann](mailto:fancoding@outlook.com).

---
<a href="https://saweria.co/FCProject">Support Me</a>
Thank you for using SA:MP DDoS v1.0.0
```