# URL Shortener Project

This project is a URL shortener service that allows users to create shortened links for long URLs.

## Features

- Shorten long URLs to compact, shareable links
- Generate QR codes for shortened links
- Track click statistics for shortened links
- Display location and device data for link clicks

## Screenshots

### Homepage
![Homepage](./homePage.png)
The homepage advertises the service as "The only URL Shortener you'll ever need!"

### Login/Signup Page
![Login/Signup](./loginPage.png)
Users can log in to existing accounts or sign up for new ones.

### Main Dashboard
![Main Dashboard](./dashboard.png)
The main dashboard shows existing shortened links, their QR codes, and options to create new links.

### Link Statistics
![Link Statistics](./analytics.png)
Detailed statistics are provided for each shortened link, including total clicks, location data, and device information.

## Usage

1. Enter the long URL you wish to shorten
2. (Optional) Customize the shortened link
3. Click "Create" to generate your shortened URL
4. Share your shortened link or use the generated QR code

## Technologies Used

- **React**: A JavaScript library for building user interfaces
- **React Router**: For handling routing in the application
- **Supabase**: A Backend-as-a-Service (BaaS) platform for database and authentication
- **Recharts**: A charting library for React
- **Tailwind CSS**: A utility-first CSS framework
- **Shadcn UI**: A collection of re-usable components built with Tailwind CSS
- **Yup**: A JavaScript schema builder for value parsing and validation
- **UA Parser JS**: A library to detect Browser, Engine, OS, CPU, and Device type/model from User-Agent data
- **React QR Code Logo**: For generating QR codes
- **React Spinners**: For loading animations

## Installation Guide

Follow these steps to set up the project locally:

1. Clone the repository:
2. Install dependencies:
3. Set up environment variables:
Create a `.env` file in the root directory and add the following variables:
4. Start the development server:
5. Open your browser and navigate to `http://localhost:5173` to view the application.

## Features

- User authentication (signup, login, logout)
- Create shortened URLs
- Custom URL slugs
- QR code generation for shortened URLs
- Dashboard to manage and view statistics for shortened URLs
- Click tracking and analytics (device type, location)

## Project Structure

- `src/components`: React components
- `src/pages`: Page components
- `src/db`: API functions for interacting with Supabase
- `src/hooks`: Custom React hooks
- `src/layouts`: Layout components
- `src/context`: React context for global state management

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
  

## Contributing

[Instructions for how others can contribute to the project]

## License

[Specify the license under which this project is released]
