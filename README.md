# Aura - Minimalist E-commerce & AI Concierge

Aura is a serene, premium e-commerce experience designed with a warm minimalist aesthetic. It focuses on "organic technology" and "quiet living," providing a calm shopping environment powered by a modern tech stack and an AI-driven shopping assistant.

## ✨ Key Features

- **Warm Minimalist Design**: A carefully crafted UI using a palette of creams and charcoals, featuring elegant typography (Playfair Display & Inter).
- **AI Shopping Assistant**: An integrated concierge powered by Gemini 1.5 Flash to help users find products, understand philosophy, and navigate the store.
- **Product Ecosystem**: Detailed product views with immersive descriptions and a seamless add-to-cart experience.
- **Journal/Editorial**: A dedicated space for "Quiet Living" articles, bridging the gap between commerce and lifestyle content.
- **Smooth Interaction**: Responsive design with custom scroll behavior and fluid layout transitions.
- **Modern Stack**: Built with React 19, Vite, and Tailwind CSS for high performance and developer productivity.

## 🛠 Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **AI Engine**: [Google Gemini API](https://ai.google.dev/) (@google/genai)
- **Language**: [TypeScript](https://www.typescriptlang.org/)

## 🚀 Getting Started

### Prerequisites

- Node.js (Latest LTS recommended)
- A Google Gemini API Key

### Installation

1. **Clone the repository** (or download the files).
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Set up Environment Variables**:
   Create a `.env` file in the root directory and add your Gemini API key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```
4. **Run the development server**:
   ```bash
   npm run dev
   ```
5. **Build for production**:
   ```bash
   npm run build
   ```

## 📂 Project Structure

- `src/App.tsx`: The main application entry point and router logic.
- `src/components/`: Reusable UI components (Navbar, Hero, ProductGrid, etc.).
- `src/services/geminiService.ts`: Integration with the Google Generative AI SDK.
- `src/constants.ts`: Store data including products, journal articles, and brand values.
- `src/types.ts`: TypeScript interfaces for consistent data structures.

## 🎨 Aesthetic Guidelines

The project follows a "Organic Technology" design philosophy:
- **Backgrounds**: Warm creams (`#F5F2EB`)
- **Text**: Deep charcoals (`#2C2A26`)
- **Typography**: Playfair Display for headings (Serif) and Inter for UI (Sans-serif).
- **Spacing**: Generous whitespace to promote a sense of calm.

---

*Part of the Aura Quiet Living Collection.*
