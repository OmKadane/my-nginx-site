# my-nginx-site

[![Nginx](https://img.shields.io/badge/powered%20by-Nginx-009639?style=flat&logo=nginx)](https://nginx.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/OmKadane/my-nginx-site)](https://github.com/OmKadane/my-nginx-site/issues)
[![GitHub stars](https://img.shields.io/github/stars/OmKadane/my-nginx-site)](https://github.com/OmKadane/my-nginx-site/stargazers)
[![Repo Size](https://img.shields.io/github/repo-size/OmKadane/my-nginx-site)](https://github.com/OmKadane/my-nginx-site)

A professional static website designed to be served by an Nginx web server, with a deployment workflow powered by Git.



---

## 📋 Table of Contents

1.  [About The Project](#about-the-project)
2.  [Built With](#built-with)
3.  [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Deployment](#deployment)
4.  [Features](#features)
5.  [License](#license)

---

## ℹ️ About The Project

This repository contains the source code for a clean, modern, and responsive static website. The primary purpose of this project is to demonstrate a powerful and efficient workflow for web development and deployment using **Nginx** as the web server and **Git** for version control and content synchronization.

This setup is ideal for portfolios, landing pages, and documentation sites where speed, security, and simplicity are top priorities.

---

## 🛠️ Built With

This project was built using fundamental web technologies:

* **HTML5**
* **CSS3**
* **Nginx** (for serving the site)
* **Git** (for version control and deployment)

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following software installed on your server or local machine:

* **Nginx:** [Installation Guide](https://nginx.org/en/docs/install.html)
* **Git:** [Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Deployment

1.  **Choose your web root directory.** For Nginx on Linux, this is typically `/var/www/html`. For our Windows setup, we used `C:\nginx\nginx-1.29.1\html`.
2.  **Clear the directory** to ensure no old files remain.
3.  **Clone the repository** directly into your web root folder. Remember to add a `.` at the end of the command to clone into the current directory.
    ```sh
    git clone [https://github.com/OmKadane/my-nginx-site.git](https://github.com/OmKadane/my-nginx-site.git) .
    ```
4.  **Restart Nginx** to ensure the new site is served correctly.
5.  Visit your server's IP address or `http://localhost` in a browser to see the live site.

---

## ✨ Features

* **Clean & Modern Design:** A professional layout suitable for any project.
* **Responsive:** Looks great on desktops, tablets, and mobile devices.
* **Optimized for Nginx:** Built to be served quickly and efficiently.
* **Git-Powered Deployment:** Easily update the live site by pushing changes to this repository.

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
