# Via-Browser-Custom-Logo

This repository contains HTML, CSS, and JavaScript code for creating a custom animated logo in Via Browser. The logo displays a random GIF from Giphy based on a specified tag and includes a loading animation while the GIF is being fetched.

![example](media/example.gif)
<img src="media/example.gif" height="400" alt="example">

## How to Use

### Prerequisites

- A Giphy API key. You can obtain one by signing up at [Giphy Developers](https://developers.giphy.com/).

### Installation

1. Clone this repository or copy the code.
2. Open the `script.js` file and replace the following placeholders with your details:
   - `<YOUR GIPHY API KEY>`: Replace with your Giphy API key.
   - `<YOUR TAG>`: Replace with the desired tag (e.g., `cat`, `funny`).

3. Open Via Browser and go to **Settings > Customization > Logo**.
4. Select the **HTML Code** option and paste the code from this repository.
5. Save the changes and restart Via Browser (if necessary).

## Troubleshooting

- **GIF Not Loading**: Ensure that the API key is entered correctly and the specified tag exists on Giphy.
- **Loading Animation Doesn't Disappear**: Check if the API request is successful.
- **Logo Displays Incorrectly**: Make sure the container size (`#gif-container`) meets your requirements.
