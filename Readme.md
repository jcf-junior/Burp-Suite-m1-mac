--------------------------------------------------------------------------------------------
# Use with M1/M2 Based Kali

## Select JDX 11:

	1. git clone https://github.com/jcf-junior/Burp-Suite-m1-mac.git
	2. sudo update-alternatives --config java
	3. Select option 1 or whichever is equal to /usr/lib/jvm/java-11-openjdk-arm64/bin/java
	3. cd Burp-Suite/
	4. sudo ./Kali_Linux_Setup.sh
	
## To activate the License:
	
	1. Copy the License key from the Keygen
	2. Paste it into the Setup
	3. Select Manual activation
	4. Copy the Activation Request key from the Setup
	5. Paste it into the Keygen
	6. A response will be generated, copy it and paste it into the Setup.
	7. Click Next and Burp should be successfully activated
	
## To start Burp in case it doesn't auto start:
	1. burp
