# Scroll Button

This dynamic scroll button helps users to quickly navigate to the most recent bar.
The button is intelligently designed to appear when the chart is scrolled back and disappear
when the chart is at the most recent bar, enhancing the user's chart navigation experience.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Inputs](#inputs)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- Button appears when you scroll back on the chart and disappears when you are at the most recent bar.
- Click the button to instantly scroll the chart to the most recent bar.
- Place the button on the chart where it is easily accessible.
- Helps traders focus on the latest market developments and make timely decisions.

## Installation

1. Download the Script: Download the Scroll Button.mq5 file from this repository.
2. Open MetaTrader 5
   - Launch MetaTrader 5.
   - Go to `File` -> `Open Data Folder`.
3. Place the Script
   - Navigate to `MQL5` -> `Indicators`.
   - Copy the `Scroll Button.mq5` file into the Indicators folder.
4. Refresh MetaTrader 5
   - Restart MetaTrader 5 or right-click in the Navigator window and select Refresh.

## Usage

1. Load the Script
   - Open MetaTrader 5.
   - In the Navigator window, find the `Scroll Button` script under `Indicators`.
   - Drag and drop the `Scroll Button` script onto the chart where you want to use it.
2. Interact with the Button
   - The "Button Scroll" button will appear at the bottom-right corner of the chart when you scroll back.
   - Click the button to immediately scroll to the most recent bar.
   - The button will disappear automatically when the chart reaches the most recent bar.

## Inputs

### 🔹 STYLE Group
| Input                    | Description                                                           |
|--------------------------|-----------------------------------------------------------------------|
| `Button size`            | Sets the width and height of the button.                              |    
| `Button color`           | Defines the background color of the button.                           |
| `Text color`             | Sets the color of the text displayed on the button.                   |

### 🔹 POSITION Group
| Input                         | Description                                                      |
|-------------------------------|------------------------------------------------------------------|
| `X distance from the corner`  | Horizontal distance of the button from the selected chart corner.|
| `Y distance from the corner`  | Vertical distance of the button from the selected chart corner.  |

## Customization

You can customize the name of the object by modifying the following text in the script.
```mql5
#define BUTTON_NAME "Scroll_Button"
```

## Contributing

Contributions are welcome! If you have any improvements, bug fixes, or new features to suggest, please follow these steps

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes with descriptive commit messages.
4. Push your branch to your forked repository.
4. Open a pull request to the main repository's main branch.
5. Please ensure your code follows the existing code style and includes comments where necessary.

Please ensure your code follows the existing code style and includes comments where necessary.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
