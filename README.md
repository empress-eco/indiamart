<div align="center">
  ![Project Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png
</div>

Effortlessly manage your leads with this powerful integration tool that seamlessly pulls lead data from Indiamart into your Empress system. Ideal for businesses leveraging both Indiamart and Empress, this integration ensures no potential leads slip through unnoticed while saving you time and effort. 

* [Explore the Documentation](https://empress.eco/)
* [Report a Bug](https://github.com/empress-eco/indiamart/issues)
* [Request a Feature](https://github.com/empress-eco/indiamart/issues)

## About The Project

**Indiamart Integration** automates lead generation by pulling data from Indiamart and creating leads in your Empress system every 20 minutes. You also have the flexibility to manually pull data or pause the operation as needed.

### Key Features
* Automatic lead generation every 20 minutes
* Option for manual data pull from Indiamart
* Easy pause operation via the hook file

## Technical Stack and Setup Instructions

This project leverages Indiamart's APIs and Empress's robust framework.

### Prerequisites
* Access to Indiamart portal to retrieve your key

### Setup
1. Retrieve your key from the Indiamart portal and set it on the 'Indiamart Setting' page.
2. Add the URL - either `https://mapi.indiamart.com/wservce/crm/crmListing/v2/` or a new one provided by Indiamart.
3. Enable the Indiamart Module

To clone and install the project, run the following commands:
```sh
git clone https://github.com/empress-eco/indiamart.git
```
Then, set your key and URL:
```sh
# Example
key: YOUR_KEY_HERE
url: YOUR_URL_HERE
```

## Usage

Post setup, the system starts pulling data from Indiamart and creating leads every 20 minutes. To pause the operation, comment the code in the hook file. For manual data pull, visit the 'Indiamart Setting' page.

## Contribution Guidelines

Contributions are always welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is licensed under the MIT License. Your contributions are covered under the same.

Special thanks to the Empress Community for their instrumental contributions in building the essential tools that power this project. We deeply appreciate their innovation, dedication, and ongoing support.