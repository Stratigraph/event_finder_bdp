## Notes
Connects to the BDP servlet to collect GDELT events.

## AWS EC2 Version Notes
Removed Google API libraries (won't execute with RHEL 6.6 c++ stdlibs)

Make sure the AWS group permits port 3000

iptables -I INPUT -p tcp -m tcp --dport 3000 -j ACCEPT

service iptables save


## Installation

Install Node Package Manager (npm) and Node.js (v4 or higher) for your OS.

Run npm install in the root of this project.

Launch the server:

node app.js

Launch the browser:

http://localhost:3000

