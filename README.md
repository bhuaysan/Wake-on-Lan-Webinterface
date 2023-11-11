# Wake-on-LAN Webinterface

Wake-on-LAN Webinterface is a simple web application built with Flask that allows you to manage and wake up devices on your local network using Wake-on-LAN. The application enables you to add, delete, and wake up devices, providing a convenient interface for managing your wake-up requests.

## Features

- **Device Management:** Add, delete, and view devices on your local network.
- **Wake-up Functionality:** Send Wake-on-LAN magic packets to wake up devices remotely.
- **Device Status:** Check the online/offline status of devices.

## Getting Started

Follow these steps to set up and run the Flask Wake-on-LAN application:

1. **Clone the Repository:**
     ```bash
     git clone https://github.com/bhuaysan/Wake-on-Lan-Webinterface.git
   
   
2. **Install Dependencies**
     ```bash
     pip install flask wakeonlan
   

3. **Run the Application**
     ```bash
     python app.py
   

## Usage

1. **Add Devices:**
    - Access the web interface and navigate to the "Add Device" page.
    - Enter the device name, MAC address, and IP address, and submit the form.

2. **Wake Up Devices:**
    - On the main page, view the list of devices.
    - Click the "Wake Up" button next to a device to send a Wake-on-LAN magic packet.

3. **Delete Devices:**
    - On the main page, view the list of devices.
    - Click the "Delete" button next to a device to remove it from the list.

4. **View Device Status:**
    - The main page displays the current online/offline status of each device.

## Configuration
The application stores device information in a JSON file named **devices.json**. Make sure this file is present in the project directory. If not, the application will create an empty list of devices.
    
## Contributing
Feel free to contribute to this project. Whether it's fixing a bug, improving the documentation, or adding new features, your contributions are welcome.

## License
This project is licensed under the MIT License.

## Acknowledgments
 - Flask: https://flask.palletsprojects.com/
 - Wake-on-LAN: https://pypi.org/project/wakeonlan/


