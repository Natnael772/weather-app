# Weather App

This is a weather app built with Next.js, TypeScript, Tailwind CSS, React Query, and Shadcn UI.

## Setup Instructions

Follow these steps to set up the project locally:

1. **Clone the project:**

```
git clone https://github.com/yoo/weatherapp
```

2. **Install nvm (Node Version Manager):**

- If you already have nvm installed, make sure you're using version 20.11.0.
- If you don't have nvm installed, you can follow the instructions at [nvm GitHub repository](https://github.com/nvm-sh/nvm) to install it.

3. **Install project dependencies:**

```
 npm install
```

4. **Obtain API key from OpenWeatherMap:**

- Go to [OpenWeatherMap API](https://openweathermap.org/api) and sign up for an account if you haven't already.
- Obtain an API key.
- Create a file named `.env.local` in the root directory of the project.
- Add your API key to the `.env.local` file:

  ```
  API_KEY=your_api_key_here
  ```

5. **Run the project:**

   ```
   npm run dev
   ```

The project should now be running locally. You can access it at `http://localhost:3000`.
