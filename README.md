# !!! -DISCLAIMER- !!!


 
This software is intended solely for personal use and educational purposes. The author accepts no liability for any consequences arising from the use of the programme. Before use, please ensure that you have permission to monitor devices and that you comply with applicable legislation.

# --- Description ---



SecureMonitor is a simple client-server application for monitoring active windows and periodically taking screenshots on client devices. The client sends screenshots and information about the active window to the server, where this data is stored and displayed via a PIN-protected web interface.

# --- Features ---



Periodic collection of screenshots and the names of active windows on client devices.

A secure server with access to logs and screenshots via a PIN code.

A web interface for viewing screenshots with timestamps and application details.

Easy to deploy and use.

# --- Donations ---



If you’d like to see this project continue or develop into a more advanced version, you can make a donation here: https://ko-fi.com/coolzero55894. This would mean that I haven’t wasted all those hours of work and effort.

# --- Installation and Setup ---



Install the dependencies:

pip install -r requirements.txt

Start the server:

python server/server.py

3. Configure and run the client (specify the server’s IP address in client.py):

python client/client.py

4. Open the following in your browser:

http://SERVER_IP:5000/

5. Enter the PIN (default: 1234) to view the screenshots.


# --- Licence ---



MIT Licence (see the LICENSE file)
