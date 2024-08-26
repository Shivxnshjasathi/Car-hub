# Car Details Website - CarHub

Welcome to the Car Details Website! This project is a Next.js application that provides detailed information about cars using the Cars API from RapidAPI.

## Features

- **Search for Cars**: Enter the car model to fetch detailed information about various cars.
- **Detailed View**: Get comprehensive details including images and specifications.
- **Responsive Design**: Fully optimized for a smooth experience on both mobile and desktop devices.

## Technologies Used

- **Next.js**: A React framework for building server-rendered React applications.
- **RapidAPI**: Provides access to the Cars API to fetch car details.
- **Tailwind CSS**: For modern, responsive styling.
- **TypeScript**: For type safety and better development experience.

## API Endpoint

This application uses the Cars API from RapidAPI to retrieve car details. The endpoint used is:

```
https://cars-by-api-ninjas.p.rapidapi.com/v1/cars?model=corolla
```

To use this endpoint, you'll need a RapidAPI account and an API key.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/car-details-website.git
cd car-details-website
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env.local` file in the root of your project and add your RapidAPI key:

```
NEXT_PUBLIC_RAPIDAPI_KEY=your-rapidapi-key
```

### 4. Run the Development Server

```bash
npm run dev
```

Navigate to `http://localhost:3000` in your browser to see the application in action.

## Usage

1. Enter the car model you want to search for in the input field.
2. Click the "Search" button to fetch and display details about the car.
3. Explore the detailed view for more information and images.

## Contributing

Feel free to open issues or submit pull requests if you'd like to contribute to the project. Please follow the standard Git workflow and include clear commit messages.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy exploring!

--- 
