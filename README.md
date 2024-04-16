

---

# Web IDE

Welcome to the Code Editor Web Integrated Development Environment! This application is a simple online code editor that allows you to write, execute, and view the output of your code in various programming languages. It is built using React and Chakra UI, and it leverages an API to execute code remotely.

## Features

- Supports multiple programming languages: JavaScript, TypeScript, Python, Java, C#, and PHP.
- Syntax highlighting and code snippets for each language.
- Run code and view output in real-time.
- Lightweight and responsive user interface.

## Technologies Used

- [React](https://reactjs.org/): JavaScript library for building user interfaces.
- [Chakra UI](https://chakra-ui.com/): Simple, modular, and accessible component library.
- [Vite](https://vitejs.dev/): Fast and modern web development build tool.
- [Axios](https://axios-http.com/): Promise-based HTTP client for making API requests.
- [Monaco Editor](https://microsoft.github.io/monaco-editor/): Code editor from Microsoft used in VSCode.

## Installation

1. **Clone the repository:**

    ```shell
    git clone <repository_url>
    ```

2. **Navigate to the project directory:**

    ```shell
    cd WEB-IDE
    ```

3. **Install dependencies:**

    ```shell
    npm install
    ```

## Usage

1. **Run the application:**

    ```shell
    npm run dev
    ```

    This command will start the application locally at `http://localhost:3000`.

2. **Start coding:**

    - Select a language from the dropdown menu.
    - Use the code editor to write your code.
    - Click the "Run Code" button to execute the code and see the output.

## Configuration

- The application's base URL for the API is configured in `src/api.js`. You can update this if needed.
- The code snippets and supported languages are defined in `src/constants.js`.

## File Structure

- `src/`: Contains the main source code for the application.
    - `components/`: Holds the React components.
    - `constants.js`: Contains constants such as supported languages and code snippets.
    - `api.js`: Handles API requests to execute code.
    - `App.jsx`: Main application file.
    - `theme.js`: Chakra UI theme configuration.
- `public/`: Contains static assets such as `index.html`.
- `vite.config.js`: Configuration file for Vite.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#).

## License

This project is licensed under the MIT License. See the [LICENSE](#) file for details.

## Acknowledgements

- [Piston](https://piston-lang.org/): Used for executing code in different languages.
- [Monaco Editor](https://microsoft.github.io/monaco-editor/): Used for the code editor interface.

---

