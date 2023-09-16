# Busy B Private Browser

**Busy B Private Browser** is a simple web browser built using PyQt5. It provides a clean and private browsing experience. The browser uses the DuckDuckGo search engine as its default search engine. It also features basic navigation buttons, a URL address bar, and a download manager.

## Features

- Private browsing mode: The browser does not store persistent cookies, ensuring your privacy while browsing.
- Basic navigation buttons: You can go back, forward, and reload webpages using the toolbar buttons provided.
- URL address bar: Enter the URL of a webpage and press Enter to load it.
- Download manager: When a file is requested for download, a prompt is displayed to confirm the download. You can track the progress of ongoing downloads and access the downloaded file once it is completed.

## Prerequisites

- Python 3.x
- PyQt5

## Getting Started

1. Clone the repository:

```
git clone https://github.com/B-Boone/Busy_B_Browser
```

**WINDOWS USERS**
2. Open the directory in File Explorer:

```
Busy_B_Browser
```

3. Double click the .exe file:

```
private_browser.exe
```

**LINUX USERS**
2. Change into the project directory:

```
cd Busy_B_Browser
```

3. Install the required dependencies:

```
sudo pip3 install PyQt5 && sudo apt-get install -y python3-pyqt5.qtwebengine
```

4. Run the browser:

```
python3 private_browser.py
```

## Usage

The Busy B Private Browser provides a user-friendly interface for browsing the web. Here's how to use the browser:

1. Enter a URL or a search query in the URL address bar.
2. Press Enter to load the webpage.
3. Use the navigation buttons to go back, forward, or reload the current webpage.
4. When a file is requested for download, a prompt will be displayed. Click "Yes" to start the download.
5. You can track the progress of ongoing downloads in the download progress bar at the bottom of the window.
6. Once a download is completed, the "Access Downloaded File" button will become enabled. Click it to open the downloaded file's directory using the default file manager.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) License.

## Acknowledgements

- The Busy B Private Browser was developed using the PyQt5 library.
- The browser's default search engine is DuckDuckGo.
- The browser icon is derived from the busyb.ico file in the project directory.
