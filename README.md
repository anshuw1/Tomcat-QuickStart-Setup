# Tomcat QuickStart Setup

## Overview

The idea of this project is to make easy an automated script optimized for Amazon Linux, simplifying the installation and configuration of the Tomcat server. It handles the entire setup process, ensuring your server is ready with minimal effort. Additionally, a scheduled job fetches the latest Tomcat version weekly, automatically updating the `tomcat.sh` file to keep your server current. Designed for user convenience, the script ensures a seamless setup, allowing you to focus on coding and deployment with a fully configured Tomcat server

## Features

- Automated installation and configuration of Tomcat on Amazon Linux.
- Scheduled job for weekly updates to the latest Tomcat version.
- Easy-to-use script with minimal setup required.
- Focus on coding and deployment with a fully configured Tomcat server.

## Prerequisites

- Amazon Linux instance
- Git installed on the instance
- Basic knowledge of Linux command line

## Installation

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/anshuw1/Tomcat-QuickStart-Setup.git
    cd Tomcat-QuickStart-Setup
    ```

2. **Run the Setup Script:**
    ```sh
    chmod +x setup.sh
    ./setup.sh
    ```

## Usage

- The script will install and configure Tomcat, ensuring it's up and running with minimal effort.
- A cron job is set up to fetch the latest Tomcat version weekly, ensuring your server remains updated.

## Updating Tomcat

The scheduled job automatically updates the `tomcat.sh` file with the latest Tomcat version. To manually update, you can rerun the setup script:
```sh
./setup.sh
