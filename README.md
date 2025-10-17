# Captcha Solver Frontend

This is a simple, responsive single-page HTML application designed to act as a frontend for a captcha solver. It utilizes Tailwind CSS for styling and vanilla JavaScript for interactivity, including dynamic image loading based on URL parameters.

## Features

*   **Responsive Design:** Adapts to various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading:** Displays a captcha image from a `url` query parameter.
*   **Default Image:** If no `url` parameter is provided, it defaults to `sample.png`.
*   **User Input:** Provides an input field for users to enter the captcha text.
*   **Simulated Submission:** The "Solve Captcha" button simulates a submission process (actual captcha solving logic would reside on a backend).

## Usage

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Default Image:** By default, the application will display `sample.png`.
3.  **Load Custom Captcha:** To display a specific captcha image, append a `url` query parameter to the URL in your browser's address bar.

    Example:
    `index.html?url=https://example.com/path/to/your/captcha.png`

4.  **Enter Solution:** Type the text you see in the captcha image into the provided input field.
5.  **Submit:** Click the "Solve Captcha" button. The application will acknowledge your input.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** Utility-first CSS framework for styling.
*   **JavaScript:** For dynamic content loading and client-side interactions.

## Local Development

No complex setup is required. Just ensure `index.html` and `sample.png` are in the same directory.