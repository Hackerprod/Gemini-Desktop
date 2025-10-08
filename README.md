# Gemini Desktop

An unofficial desktop client for Gemini, which wraps the web interface in a Windows application using C# and WPF.

## Features

*   **WebView Interface:** Loads the Gemini web interface (`gemini.google.com`).
*   **Dark Theme:** The window and title bar have a dark color (`#202124`) for an integrated look.
*   **Custom Icon:** Uses a custom application icon.
*   **No White Flash:** The window does not show a white flash on loading; it waits for the content to be ready before appearing.

## How to Build and Run

1.  **Clone the repository (if needed):**
    ```bash
    git clone https://github.com/Hackerprod/Gemini-Desktop.git
    cd Gemini-Desktop
    ```

2.  **Restore dependencies and build:**
    ```bash
    dotnet build
    ```

3.  **Run the application:**
    *   From the command line:
        ```bash
        dotnet run
        ```
    *   Or by running the `.exe` file directly from the build folder:
        `bin\Debug\net8.0-windows\Gemini Desktop.exe`

## Requirements

*   .NET 8 SDK or higher.
*   The WebView2 Runtime (normally pre-installed with Microsoft Edge on Windows 10/11).