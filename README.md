#  DZDraw — Algerian Digital Drawing App

**DZDraw** is a modern and responsive digital drawing application designed for both **mobile devices and browsers**. Built with **React**, **Fabric.js**, and **Tailwind CSS**, it lets you create artwork effortlessly using a sleek and intuitive interface.

 **Live Demo:** https://dzdraw.netlify.app/

# white mode

<img width="1920" height="922" alt="image" src="https://github.com/user-attachments/assets/efd0b776-9abf-43b6-986f-8a338664e075" />

---
# dark mode

<img width="1920" height="922" alt="image" src="https://github.com/user-attachments/assets/98e0a969-5147-4f71-8294-40c3e41adb75" />

---

##  Features

-  **Free Drawing** — Smooth drawing experience with customizable brush settings  
-  **Color Picker** — Choose from 8 preset colors: black, purple, blue, green, orange, red, pink, and white  
-  **Brush Thickness Control** — Adjust width from 1 to 20px with a live preview  
-  **Undo** — Remove the last object instantly  
-  **Clear Canvas** — Reset and start fresh with one click  
-  **Save as PNG** — Download your artwork locally  
-  **Auto-Save** — Automatically stores your drawings every 5 seconds using Local Storage  
-  **Light / Dark Theme** — Switch the entire UI with a single toggle  
-  **Responsive Design** — Works seamlessly on phones, tablets, and desktops

---

## 🛠 Tech Stack

| Technology   | Usage                         |
|--------------|-------------------------------|
| React 18     | UI Framework                  |
| TypeScript   | Type Safety                   |
| Vite         | Dev Server & Bundler          |
| Fabric.js 6  | Canvas Rendering & Editing    |
| Tailwind CSS | Styling System                |
| shadcn/ui    | UI Components                 |
| Lucide React | Icons                         |

---

##  Installation & Setup

###  Prerequisites

- **Node.js** ≥ 16  
- **npm** or **bun**

###  Install

```bash
git clone https://github.com/Mohamedboukerche22/DZ-Draw
cd DZ-Draw
```

# Install dependencies
```bash
npm install
# or
bun install
```

# Run development server
```bash
npm run dev
# or
bun run dev
```

Now visit: `http://localhost:5173`

 Build for Production
```bash
نسخ الكود
npm run build
# or
bun run build
```
Output will be located in the /dist directory.

## Usage Guide
Action	How to Use
Start Drawing	Click the pencil icon
Change Color	Select from the color palette
Adjust Brush Size	Drag the thickness slider
Undo Last Action	Click the undo button
Clear Canvas	Click the trash icon
Save as Image	Click the download icon
Toggle Theme	Switch light/dark mode

##📁 Project Structure
```bash
نسخ الكود
src/
├── components/
│   ├── DrawingCanvas.tsx    # Main canvas component
│   ├── ColorPicker.tsx      # Color selection component
│   ├── Toolbar.tsx          # Action buttons
│   ├── ThicknessSlider.tsx  # Brush size controller
│   └── ui/                  # shadcn/ui components
├── pages/
│   └── Index.tsx            # Main page
├── lib/
│   └── utils.ts             # Utilities
└── main.tsx                 # App entry point
```

🤝 Contributing
Contributions are welcome and appreciated!
Feel free to open an issue or submit a PR.

📜 License
MIT License — free to use and modify.

Made with ❤️ in Algeria 🇩🇿
نسخ الكود
