# m3-w4-d1-demo
Web-602-Spring 2025

## Setup Instructions

1. Install Less globally using npm:
    ```sh
    npm install -g less
    ```

2. Convert `.less` files to `.css` using the `lessc` command:
    ```sh
    lessc path/to/input.less path/to/output.css
    ```

3. Add the generated CSS into your HTML files:
    ```html
    <link rel = "stylesheet" href = "path/to/output.css" type = "text/css">
    ```