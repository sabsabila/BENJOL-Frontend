# Kuy Belajar React JS!

[**React JS**](https://reactjs.org/) adalah sebuah framework JavaScript yang dibuat untuk membangun aplikasi front-end berbasis web. Dalam tutorial kalian bisa mempelajari semua hal dasar yang perlu diketahui untuk membangun aplikasi front-end web menggunakan **React JS**.

## References

Sebelum masuk ke komponen dan koding, ada beberapa link referensi yang berisi informasi perihal apa itu **React JS** dan mengapa belajar **React JS ** dapat bermanfaat untuk kalian:

- [What Is React (React js) & Why Is It So Popular?](https://www.youtube.com/watch?v=N3AkSS5hXMA)
- [Tutorial Resmi React JS](https://reactjs.org)

## Roadmap

![React JS roadmap](https://roadmap.sh/roadmaps/react.png)
Eits, jangan keburu pusing dulu setelah melihat gambar ini, meskipun terlihat banyak sekali yang perlu dipelajari untuk bisa membangun aplikasi web menggunakan **React JS**, tapi sebenarnya hal itu justru mempermudah developer dalam mengembangkan aplikasi, karena banyak sekali library atau komponen yang dapat digunakan untuk membangun aplikasi web dengan praktis.

## Fundamental Topics

Sebelum masuk ke **React JS**, kita harus lebih dulu memahami bahasa pemrograman JS atau **JavaScript**. Bahasa pemrograman **JavaScript** dapat dipelajari dengan cepat karena bersifat sederhana dan fleksibel. Kalian dapat mempelajari dasar dasar pemrograman JavaScript disini:
[# A re-introduction to JavaScript (JS tutorial)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

Apabila sudah memahami JavaScript, sekarang waktunya kita masuk ke **Fundamental React JS**

### 1. Instalasi dan Create App

- Install npm and Node JS: https://www.npmjs.com/get-npm
- Run `npx create-react-app` atau clone starter dari: [react js starter anggapradipta](https://github.com/pradiptakp/react-101/branches)
- Apabila melakukan clone, run `npm install` untuk melakukan install _node modules_ atau kumpulan dari library yang terdaftar di package.json
- Untuk run debug bisa gunakan `npm start`

> Referensi: [Learn React In 30 Minutes](https://www.youtube.com/watch?v=hQAHSlTtcmY)

### 2. JSX

**JSX** adalah bahasa yang digunakan untuk menulis view komponen dari **React JS**, syntax **JSX** sendiri tidak jauh berbeda dengan HTML. Contoh dari penulisan **JSX** dapat dilihat di App.js.

> Referensi:
>
> - https://www.w3schools.com/react/react_jsx.asp
> - https://reactjs.org/docs/introducing-jsx.html

### 3. Functional vs Class Components

Pengunaan function dan class dalam penulisan koding memiliki perbedaan syntax dan fungsional yang mempengaruhi pengolahan data dalam React

> Referensi:
> https://medium.com/@Zwenza/functional-vs-class-components-in-react-231e3fbd7108

### 4. Props vs State

Props & State adalah komponen yang dapat digunakan untuk menyimpan dan mengolah data dalam **React JS**

> Referensi:
> https://flaviocopes.com/react-state-vs-props/

### 5. Conditional Rendering

Dengan menggunakan data dari props atau state, developer dapat melakukan conditional rendering yaitu dengan melakukan rendering komponen **JSX** menyesuaikan dengan kondisi dari data baik menggunakan state atau props

> Referensi:
> https://linguinecode.com/post/4-techniques-conditional-render-react-props-state

### 6. Component Life Cycle

**Component Life Cycle** adalah siklus dari komponen yang digunakan untuk me-render tampilan dari web. Siklus ini memang terlihat agak rumit, beruntung nya sekarang sudah ada hooks yang salah satu kegunaannya adalah untuk menyederhanakan life cycle dari **React JS**.

> https://medium.com/codeacademia/apa-itu-component-lifecycle-di-react-bfcb64f64e0e

### 7. List & Keys

Dengan List & Keys developer dapat menampilkan tampilan berulang secara mudah menggunakan fungsi `.map`

> Referensi:
> https://reactjs.org/docs/lists-and-keys.html

### 8. Composition vs Inheritance

Ini adalah salah satu komponen yang membuat **React JS** populer. Komposisi memungkinkan developer untuk membungkus komponen dalam komponen yang membuat tampilan web mudah untuk dirancang dan membuat kode menjadi lebih rapi.

> Referensi:
> https://reactjs.org/docs/composition-vs-inheritance.html

### 9. Basic Hooks

React Hooks mempermudah developer dalam melakukan manajemen _Life Cycle_ dari komponen react dan juga mengolah data. Sebelum hooks syntax syntax bawaan dari React seperti `this.setState` dan `this.state` serta fungsi _Life Cycle_ dari React seperti `componentWillMount` dan `componentDidMount` masih sering digunakan. Namun dengan adanya Hooks, semua itu dapat di handle oleh beberapa fungsi dasar seperti `useState` dan `useEffect`.

> Referensi:
>
> - https://reactjs.org/docs/hooks-intro.html
> - https://www.valentinog.com/blog/hooks/
