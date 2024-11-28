# CodeLenz

> **Bringing Code Clarity into Focus**

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [How It Works](#how-it-works)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

**CodeLenz** is a Next.js web application that transforms code into interactive, colorful visualizations. By highlighting various elements and structures within the code, CodeLenz makes it easier to read, analyze, and engage with complex codebases.

## Key Features

- **Segmented Visualization**: Automatically color-codes segments like keywords, functions, variables, and more.
- **Enhanced Readability**: Distinct color highlights for different code components.
- **Interactive Timeline**: Zoom into specific code lines and hover for details.
- **Dark Mode Toggle**: Switch between dark and light themes for a personalized experience.
- **Image Export**: Capture and download the visualized timeline as an image.

## How It Works

1. **Input Code**: Paste or type your code into CodeLenz.
2. **View Timeline**: Code is broken down into color-coded segments, making structure and patterns clear.
3. **Export and Share**: Download the visualized timeline as an image for easy sharing.

## Tech Stack

- **Frontend**: Next.js with React, using Tailwind CSS for styling.
- **Editor & Visualization**: Ace Editor for code input and D3.js for custom color-coded segments.
- **Libraries**: `html2canvas` for exporting visualizations, `lucide-react` for icons.

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rishabh3562/CodeLenz.git
   ```
2. Install dependencies:
   ```bash
   cd codelenz
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

### Usage

1. Open `http://localhost:3000` in your browser.
2. Paste or type your code to see the interactive visualization.
3. Use the toolbar options to export the timeline or switch themes.

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the **AGPL-3.0 License** - see the [LICENSE](./LICENSE) file for details.

### AGPL-3.0 License Summary:

The **Affero General Public License (AGPL-3.0)** is a free software license designed to ensure that the source code of a project remains open and freely available, even if the software is used over a network.

- **You are free to use, modify, and distribute** the software, provided that you include the source code when distributing it or when you provide it to users over a network.
- **You must make your modified source code available** if you modify and use the software to offer services over a network.
- If you **distribute the software or modified versions**, you must do so under the same AGPL-3.0 license.

### Consequences of AGPL-3.0:

1. **Network Use Requirement**: If you run the software on a server and provide access to others over the internet (i.e., software as a service), you are required to make the source code available to the users of your service.
2. **Modification Disclosure**: If you modify the software and distribute it, or make it available over a network, you must provide the modified source code under the same AGPL-3.0 license.
3. **No Proprietary Use**: You cannot convert the software into proprietary software. All copies, modifications, or derivative works must remain open and licensed under the AGPL-3.0.

Failure to comply with the terms of the AGPL-3.0 license can result in legal consequences, including the loss of rights to use, modify, or distribute the software.
