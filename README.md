# Pokédex 🚀

Welcome to **Pokédex** – a modern, full-stack Pokémon exploration app built with Next.js, TypeScript, and Prisma! 🦸‍♂️

## 🌟 Features

- 🔍 **Search Pokémon** by name, type, and abilities.
- 🔐 **Authentication with Auth0** for a secure experience.
- 🏆 **Build your own Pokémon Team** and manage favorites.
- 🎛 **Advanced Filtering** based on type, abilities, weight, height, and order.
- 🌍 **Global State Management** with a custom solution for seamless data handling.
- ⚡ **Custom API State Management** to optimize API calls.
- 🔄 **Infinite Scrolling** for a smooth user experience.
- 🗄 **MongoDB + Prisma** for efficient database operations.

## 🛠️ Tech Stack

- **Next.js** 🚀
- **TypeScript** 🦾
- **Auth0** 🔐
- **MongoDB & Prisma** 🗄
- **Framer Motion** 🎨 (For smooth animations)
- **ShadCN UI** 💅 (For beautiful UI components)

## 🏗️ Challenges & Failures

During development, several roadblocks were encountered:

- ❌ **Auth.js integration led to team-building errors.**
- ❌ **Hydration Errors** due to mismatches between server and client rendering.
- ❌ **Zustand for Global State Management** had unexpected behavior.
- ❌ **Infinite Scroll Issue** – initially caused a page reset.
- ❌ **SWR for API Fetching** led to incorrect API calls and `useState` conflicts.

Each of these failures helped refine the project and build a more robust application. 💪

## 📺 Credits & Inspiration

This project was inspired by the fantastic tutorial by [The Code Dealer](https://www.youtube.com/watch?v=-oq0VOQz-2w&ab_channel=TheCodeDealer). 🎥

Some UI components were also sourced from various free resources to enhance the user experience. 🎨

## 🚀 Getting Started

### 1️⃣ Clone the repository
```sh
git clone https://github.com/yourusername/pokedex.git
cd pokedex
```

### 2️⃣ Install dependencies
```sh
yarn install  # or npm install
```

### 3️⃣ Set up environment variables
Create a `.env.local` file and add the required variables:
```env
AUTH0_SECRET=your_secret
AUTH0_BASE_URL=http://localhost:3000
AUTH0_ISSUER_BASE_URL=https://your-auth0-domain
AUTH0_CLIENT_ID=your_client_id
AUTH0_CLIENT_SECRET=your_client_secret
DATABASE_URL=mongodb+srv://your_mongo_connection
```

### 4️⃣ Run the project
```sh
yarn dev  # or npm run dev
```

### 5️⃣ Enjoy catching Pokémon! 🎉

## 🤝 Contributing

Feel free to fork this repo, make changes, and submit a pull request! Let's make this the best Pokédex out there! 🔥

## 📜 License

This project is licensed under the MIT License. Happy coding! 💻

