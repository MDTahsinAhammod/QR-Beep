# QR-Beep Test Fork

QR-Beep is a project designed to scan QR codes and emit a beep sound upon successful scanning.

## Features

- Scan QR codes
- Emit beep sound on successful scan
- User-friendly interface


## Usage

1. CDN Link:
    ```html
    <script src='https://github.com/MDTahsinAhammod/QR-Beep/qrb.js'></script>
    ```

2. Generate Sound Signal:
    ```html
    <script>
        const text = 'Hello World'
        qrb.encodeData(text)
    </script>
    ```
2. Scan Sound Signal:
    ```html
    <script>
       qrb.scan((output_data) = {
        console.log(output_data)
       })
    </script>
    ```



## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License.
