# Customer Monitoring System

The Customer Monitoring System is a Python-based application that uses computer vision techniques to monitor customer activity in a physical space. The system detects the presence of customers and captures images when a new customer enters the frame. It then sends an email notification with the captured image to a specified email address.

## Features

- Real-time video monitoring of a specified camera feed
- Detection of new customers entering the frame using computer vision techniques
- Capture of images when a new customer is detected
- Email notification with the captured image to a specified email address
- Clean-up of captured images after a specified time interval

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/customer-monitoring-system.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Create a folder named `images` in the same directory.
## Usage

1. Update the `main.py` file with the appropriate camera settings and email credentials.

2. Run the application:
   ```
   python main.py
   ```

3. The application will start monitoring the specified camera feed. When a new customer is detected, an email notification with the captured image will be sent to the specified email address.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was inspired by the need for an automated customer monitoring system in retail and other similar environments.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## Support

For any questions or issues, please contact [subhojitguin2004@gmail.com](mailto:subhojitguin2004@gmail.com).

## Authors

- Subhojit Guin - [SubhojitGuin](https://github.com/SubhojitGuin)

## Resources

- [OpenCV Documentation](https://docs.opencv.org)
- [Python Email Library Documentation](https://docs.python.org/3/library/email.html)

## Disclaimer

The Customer Monitoring System is intended for educational and informational purposes only. The authors and contributors are not responsible for any misuse or illegal use of this application.

Please ensure compliance with local laws and regulations when using this system.

## Roadmap

- Implement additional features for customer behavior analysis
- Enhance email notification with additional details and insights
- Improve accuracy and efficiency of customer detection algorithm
- Integrate with other monitoring systems and analytics platforms

We welcome any feedback and contributions to help make this project even better!
