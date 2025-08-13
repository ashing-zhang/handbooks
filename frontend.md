1.ReactDOM

> - 报错：ReferenceError: ReactDOM is not defined
>       at <anonymous>:249:17
>       at pEe (https://unpkg.com/@babel/standalone/babel.min.js:3:3039570)
>       at n (https://unpkg.com/@babel/standalone/babel.min.js:3:3039821)
>       at a (https://unpkg.com/@babel/standalone/babel.min.js:3:3040184)
>       at d.src.i.onreadystatechange (https://unpkg.com/@babel/standalone/babel.min.js:3:3040441)
> - 解决方案：将 index.html 文件中的 ReactDOM CDN 链接从 https://unpkg.com/react-dom@18/umd/react-dom-client.browser.development.js 修改为 https://unpkg.com/react-dom@18/umd/react-dom.development.js 。