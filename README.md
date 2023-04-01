AI_Shirt_Designer is a web application that lets users design and preview custom shirts using DALL-E and 3D technology. With this app, users can input any text they want and have DALL-E generate unique designs based on their input. Users can also choose from a variety of shirt colors and styles to customize their design further.  Once a design is created, users can see it in real-time on a 3D shirt model, which allows them to view their creation from every angle. This makes it easier to make any necessary changes or modifications before placing an order.  

The app is built using modern web technologies, including React and Three.js, and is hosted on GitHub Pages. It also utilizes the DALL-E API to generate the designs, which allows for a seamless and efficient user experience.  Whether you're looking to create a one-of-a-kind shirt for yourself or for your business, AI_Shirt_Designer is the perfect tool for bringing your ideas to life.



## Client folder
1. npm create vite@latest -- --template react client
2. cd client
3. npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion  

https://tailwindcss.com/docs/guides/vite#react
4. npm install -D tailwindcss postcss autoprefixer
5. npx tailwindcss init -p

## Server folder
1. cd ..
2. cd D:\ReactProjects\3d_AI_product_generator\server
3. npm init -y
4. npm install cloudinary cors dotenv express mongoose nodemon openai

run server live on localhost:8080
5. npm start
