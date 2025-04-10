# HomeBanner2 - Workout Carousel

This is a React component built using **Swiper.js** to showcase different workout categories in a sliding carousel.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Features
- **Responsive Design**: Adjusts slides based on screen size.
- **Clickable Slides**: Redirects users to the respective workout details page.
- **Dynamic Data**: Displays workout type, duration, and image.
- **Pagination Support**: Users can navigate slides easily.

## Screenshot
![Workout Carousel](your-image-path.png)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/home-banner2.git
   cd home-banner2
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the project:
   ```bash
   npm start
   ```

## File Structure
```
📂 home-banner2
│── 📜 README.md
│── 📜 package.json
│── 📂 src
│   │── 📜 HomeBanner2.tsx
│   │── 📜 HomeBanner2.css
│   └── ...other files
```

## Usage
- Import `HomeBanner2` in your main file (e.g., `App.tsx`) and use it as follows:
  ```tsx
  import HomeBanner2 from './HomeBanner2';
  function App() {
    return (
      <div>
        <HomeBanner2 />
      </div>
    );
  }
  export default App;
  ```

## Learn More
To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## Technologies Used
- **React.js**
- **Next.js**
- **TypeScript**
- **Swiper.js**
- **CSS**

## License
This project is licensed under the MIT License.

---
Feel free to customize this README as per your requirements!

![image](https://github.com/user-attachments/assets/a6d898bd-b9bb-4d23-b004-30626bf38b38)
