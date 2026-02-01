# 🏡 homelab-dietpi - Simple Home Services with Ease

[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen.svg)](https://github.com/doramon12/homelab-dietpi/releases)

## 🚀 Getting Started

Welcome to homelab-dietpi! This application helps you run essential home services on your Raspberry Pi with Docker Compose. You don't need any programming experience to get started. Just follow these simple steps to set everything up.

## 📥 Download & Install

To get started, visit this page to download [the latest release](https://github.com/doramon12/homelab-dietpi/releases). On that page, you will find several versions of the software. 

1. Click on the version you want to use. The latest version is usually the best option.
2. Download the file that matches your system. If you're using a Raspberry Pi, look for the `arm64` or `armhf` files.
3. Once downloaded, follow the instructions below to set it up on your device.

## 💻 System Requirements

- Raspberry Pi (any model)
- DietPi OS (recommended for ease of use)
- Internet connection  

## ⚙️ Installation Steps

1. **Prepare Your Raspberry Pi**  
   Ensure your Raspberry Pi is set up with DietPi. If you haven’t installed DietPi yet, you can follow the official DietPi installation guide [here](https://dietpi.com/docs/).

2. **Install Docker and Docker Compose**  
   You need Docker and Docker Compose to run the application. Follow these steps:

   - Open your terminal on the Raspberry Pi.
   - Run the following command to install Docker:
     ```bash
     wget -qO- get.docker.com | sh
     ```
   - Once Docker is installed, install Docker Compose with:
     ```bash
     sudo apt-get install docker-compose
     ```

3. **Clone the Repository**  
   After installing Docker, download homelab-dietpi by running:
   ```bash
   git clone https://github.com/doramon12/homelab-dietpi.git
   ```

4. **Navigate to the Directory**  
   Change your directory to the downloaded repository:
   ```bash
   cd homelab-dietpi
   ```

5. **Launch the Docker Containers**  
   Now, you can start the application using Docker Compose. Run:
   ```bash
   docker-compose up -d
   ```
   This command will download all necessary images and start the services.

## 🛠️ Available Services

homelab-dietpi offers several useful services that help enhance your home setup:

- **Grafana:** For monitoring and visualizing your data.
- **InfluxDB:** A time-series database for storing metrics and events.
- **Nginx:** A high-performance web server.
- **Pi-hole:** A network-wide ad blocker.

## 🌟 Customizing Your Setup

You can customize your setup by editing the `docker-compose.yml` file. This file defines all services and settings used in the project. Feel free to adjust ports, volume mounts, and environment variables according to your needs.

## 📚 Troubleshooting

If you encounter any issues during setup:

- Ensure Docker and Docker Compose are correctly installed.
- Check the logs for any errors by running:
  ```bash
  docker-compose logs
  ```
- Search the internet for solutions using specific error messages.

## 🔗 Helpful Links

- [DietPi Documentation](https://dietpi.com/docs/)
- [Docker Documentation](https://docs.docker.com/)
- [Docker Compose Documentation](https://docs.docker.com/compose/)

## 📞 Support

If you have questions or need help, consider raising an issue in the [Issues tab of this repository](https://github.com/doramon12/homelab-dietpi/issues). We are here to help.

## 🔍 Next Steps

Get started by visiting this page to download [the latest release](https://github.com/doramon12/homelab-dietpi/releases). Enjoy exploring the services available to you on your Raspberry Pi!