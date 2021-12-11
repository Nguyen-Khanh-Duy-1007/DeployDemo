**1. Installing TailWindCSS**
- 
```
    npm init -y
```
```
    npm install -D tailwindcss postcss autoprefixer vite
```
```
    npx tailwindcss init -p
```
- Tạo thư mục css và file css/tailwind.css
import 3 dòng sau: 
```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```
```
    npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css
```
- Vào file package.json chuyển "test" : "..."->"dev" : "vite"
```
    npm run dev
```

**2. Class Name**
-
- Text color
```
    text-[color]-[number] 
                            Ex: text-yellow-400
```
>> https://tailwindcss.com/docs/text-color

>> https://tailwindcss.com/docs/customizing-colors

- Font Size
```
    text-[size]
                            Ex: text-6xl
```

>> https://tailwindcss.com/docs/font-size

- Font style
```
    font-[style]
                            Ex: font-bold, font-semibold
```

