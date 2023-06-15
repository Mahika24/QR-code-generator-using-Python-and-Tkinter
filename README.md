
# QR code generator using Python and Tkinter


A QR Code Generator using Python and Tkinter is a software application that allows users to generate QR codes for various types of data, such as URLs, text, and contact information. The application is built using the Python programming language and the Tkinter library, which is a built-in library in Python for creating graphical user interfaces (GUIs).

The application's main interface is a simple window with a text entry field for the user to enter the data they want to encode in the QR code and a button to generate the code. The user can enter a URL, and the application will create a QR code that can be scanned by a mobile device to automatically open the URL in a browser.

The application uses the pyqrcode library to generate the QR code, which is a pure-Python QR Code generator that creates QR codes in various formats, including svg, bmp, and png.

Once the QR code is generated, the application uses the PIL library to open the QR code image, resize it and then display it in the GUI using Tkinter's PhotoImage class.

Overall, this QR code generator is a useful tool for creating QR codes quickly and easily, and it can be useful in various scenarios such as promoting a website, sharing contact information, and many mor

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Appendix

An appendix for a QR code generator using Python and Tkinter could include the following information:

System requirements: The minimum required version of Python and any other necessary dependencies or libraries that need to be installed.

Installation instructions: A step-by-step guide on how to set up and run the application on different operating systems.

User guide: Detailed instructions on how to use the application, including how to enter data, generate QR codes, and save or share the codes.

Troubleshooting guide: Tips and solutions for common issues that users may encounter while using the application, such as missing dependencies or errors in the code.

Source code: The complete source code of the application, along with comments and documentation to help users understand how the code works.

Examples: Samples of QR codes generated by the application for different types of data, such as URLs, text, and contact information, along with the corresponding input data.

Limitations: Any known limitations of the application, such as the maximum size of data that can be encoded in a QR code.

Future work: Ideas for future enhancements or improvements to the application that the developer plans to work on.

References: A list of any external resources or libraries used in the development of the application, along with links to their documentation.









## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Deployment

To deploy this project run

```bash
  npm run deploy
```







## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform

 

## License

[MIT](https://choosealicense.com/licenses/mit/)





![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)







## Support

For support, email guptalily2002@gmail.com or join our Slack channel.
