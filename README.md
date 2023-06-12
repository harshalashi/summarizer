# Article Summarizer

![](https://github.com/harshalashi/summarizer/blob/master/ezgif.com-video-to-gif.gif)

This is a web application built with ReactJS, Tailwind CSS, and the OpenAI GPT-4 API. The purpose of this tool is to save the reader's time by providing a summary of an article instead of having to read the entire article.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Demo

You can try out the application live at [https://6486c9eda16db5259ab050e4--incomparable-donut-2994f2.netlify.app/](#).

## Features

- Paste the link of an article to be summarized.
- The tool will utilize the OpenAI GPT-4 API to summarize the article.
- The summarized article will be displayed within 10 to 15 seconds.
- Responsive design using Tailwind CSS.

## Installation

To run this project locally, please follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/article-summarizer.git
   ```

2. Navigate to the project directory:

   ```bash
   cd article-summarizer
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your OpenAI API key:

   ```env
   REACT_APP_OPENAI_API_KEY=your_api_key
   ```

   Note: You need to have an OpenAI GPT-4 API key to use this application.

5. Start the development server:

   ```bash
   npm start
   ```

6. Open your browser and visit `http://localhost:3000` to see the application.

## Usage

1. Open the application in your browser.

2. Paste the link of the article you want to summarize into the provided input field.

3. Click the "Summarize" button.

4. Wait for the tool to generate the summary, which typically takes 10 to 15 seconds.

5. The summarized article will be displayed on the screen.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to create an issue or submit a pull request.
