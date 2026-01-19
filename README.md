# Airbnb Clone 🏠

A high-performance, responsive Airbnb clone built with **Next.js**, **Tailwind CSS**, and **Mapbox**.

![Project Preview](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_B%C3%A9lo.svg/2560px-Airbnb_Logo_B%C3%A9lo.svg.png)

## 🚀 Features

- **SSR & SSG**: Utilizing Next.js for optimal performance and SEO.
- **Tailwind CSS**: A fully responsive and modern UI.
- **Mapbox Integration**: Interactive map results for search queries.
- **Date Range Picker**: Intuitive date selection for booking.
- **Live Search**: Robust search functionality with location and guest count.
- **Custom Components**: Reusable UI components including `SmallCard`, `MediumCard`, `LargeCard`, and `InfoCard`.

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Map**: [Mapbox](https://www.mapbox.com/)
- **Icons**: [Heroicons](https://heroicons.com/)
- **Date Picking**: [React Date Range](https://github.com/hypeserver/react-date-range)

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/barisariburnu/nextjs-airbnb-clone.git
   cd nextjs-airbnb-clone
   ```

2. **Install dependencies:**
   ```bash
   bun install
   # or
   npm install
   ```

3. **Set up Environment Variables:**
   Create a `.env.local` file in the root directory and add your Mapbox key.
   ```env
   NEXT_PUBLIC_MAPBOX_KEY=your_mapbox_api_token
   ```

4. **Run the development server:**
   ```bash
   bun run dev
   # or
   npm run dev
   ```

5. **Open the browser:**
   Navigate to `http://localhost:3000` to see the result.

## 📁 Project Structure

- `components/`: Pure UI components.
- `pages/`: Next.js pages and routing.
- `public/`: Static assets.
- `styles/`: Global styles and Tailwind configuration.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
