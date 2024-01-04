# Mediocre: A Next.js-based Blogging Platform

![mediocre-high-resolution-logo-transparent](https://github.com/syarwinaaa09/Mediocre/assets/114587158/08e0040e-adf6-44cf-80a2-9ce153a215eb)

Welcome to Mediocre, a modern and feature-rich blogging platform built on Next.js, TypeScript, Sanity CMS, React, Tailwind CSS, and Incremental Static Regeneration (ISR). With the goal of creating the next generation of Medium, we strive to provide a seamless and enjoyable writing and reading experience.

### Features
* **Next.js**: Utilizing the power of Next.js for a fast and efficient web experience.
* **TypeScript**: Enhancing the codebase with static typing for improved developer productivity.
* **Sanity CMS**: A robust headless CMS for managing and organizing content effortlessly.
* **React**: Building responsive and interactive user interfaces.
* **Tailwind CSS**: Styling with a utility-first approach, making it easy to customize and maintain.
* **Incremental Static Regeneration (ISR)**: Ensuring optimal performance and content delivery.

### Getting Started
To get started with Mediocre, follow these steps:

1. Clone the repository:
```
git clone https://github.com/syarwinaaa09/Mediocre.git
cd mediocre
```

2. Install dependencies:
```
npm install
```
3. Set up your Sanity CMS project and configure the necessary environment variables. Refer to Configuration for more details.

4. Run the development server:
```
npm run dev
```
5. Open `http://localhost:3000` in your browser to access Mediocre.

### Folder Structure
The project structure is organized as follows:

* `components`: React components used throughout the application.
* `pages`: Next.js pages for routing.
* `public`: Static assets (images, stylesheets, etc.).
* `styles`: Stylesheets, including Tailwind CSS configuration.
* `utils`: Utility functions and helper files.

### Configuration
Configuration for Mediocre is managed through environment variables. Create a `.env.local` file in the root directory and add the following variables:
```
SANITY_PROJECT_ID=your-sanity-project-id
SANITY_DATASET=your-sanity-dataset
```
Replace `your-sanity-project-id` and `your-sanity-dataset` with your actual Sanity CMS project ID and dataset name.

### Development
During development, you can make use of hot-reloading by running:
```
npm run dev
```
This will start the development server, and you can view your changes in real-time.

### Production
For a production build, use:
```
npm run build
npm start
```
This will build the application for production and start the server.

### Contributing
Contributions are welcome! If you have any ideas, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

### License
This project is licensed under the MIT License. Feel free to use and modify the code for your own projects.

Happy coding! 🚀

### Credits
Syarwina Ridwan
