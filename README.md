<h1 align="center">
  Gatsby Starter Zoomkoding
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-starter-zoomkoding/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-0BSD-blue.svg" alt="Gatsby Starter Zoomkoding is released under the 0BSD license." />
  </a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" alt="contributions welcome" />
</p>

[**Demo Website**](https://gatsby-starter-zoomkoding.netlify.app)

## π μκ°

μμκ³  κΉλνλ©΄μ κ²μ μμ§ μΉνμ μΈ κ°λ° λΈλ‘κ·Έλ₯Ό λ§λ€κ³  μΆμΌμ  κ°λ°μλΆλ€μ μν΄ λ§λ€κ² λ λΈλ‘κ·Έ νλ§μλλ€.π  

> PR, μ΄μ λͺ¨λ μμ²­λκ² νμν©λλ€! π

## β¨ κΈ°λ₯

- π λ―Έλͺ¨μ§μ λ¬Έμ μ λλ©μ΄μλ₯Ό ν΅ν μκΈ° μκ°
- π μ½λ νμ΄λΌμ΄ν κΈ°λ₯
- π κΈ λͺ©μ°¨ μλ μμ±(ToC)
- π¬ Utterances λκΈ κΈ°λ₯ μ§μ
- βοΈ meta-configλ₯Ό ν΅ν μΈλΆ μ€μ  κ°λ₯
- π¨βπ» About Page λ΄μ© λ³κ²½ κ°λ₯
- π Posts Page μλ μμ±
- π  sitemap.xml, robots.txt μλ μμ±
- π Google Analytics μ§μ
- π§’ Emoji μ§μ
- π Mathjax μ§μ

## π μμνκΈ°

μλ κ³Όμ μ μ§ννλ©΄ νμ¬ λΈλ‘κ·Έλ₯Ό λ‘μ»¬ νκ²½μμ μ€ννκ³  λ°°ν¬ν  μ μμ΅λλ€. 

### π§ μ€μΉνκΈ°

μλ λ²νΌμ νμ©νλ©΄ κ°μΈ κ³μ μ `gatsby-starter-zoomkoding`λ₯Ό μ¬μ©νκ³  μλ Repository μμ±κ³Ό Netlifyμ λ°°ν¬λ₯Ό λμμ μ§νν  μ μμ΅λλ€. μ΄νμ, μμ±λ Repositoryλ₯Ό cloneν©λλ€.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/zoomkoding/gatsby-starter-zoomkoding)

### πββοΈ μ€ννκΈ°

μλ λͺλ Ήμ΄λ₯Ό μ€ννμ¬ λ‘μ»¬ νκ²½μ λΈλ‘κ·Έλ₯Ό μ€νν©λλ€.

```bash
# Install dependencies
$ npm install

# Start development server
$ npm start
```
<br/>

μ λͺλ Ήμ΄κ° λ¬Έμ  μμ΄ μ€νλλ€λ©΄ [http://localhost:8000](http://localhost:8000)μμ λΈλ‘κ·Έλ₯Ό νμΈνμ€ μ μμ΅λλ€.

## βοΈ κΈ°λ³Έ μ λ³΄ μλ ₯νκΈ°

gatsby-meta-config.jsλΌλ νμΌμ λ΄μ©μ μμ νλ©΄ λΈλ‘κ·Έμ μ¬λ¬ λ΄μ©μ λ³κ²½ν  μ μμ΅λλ€!

### 1. default
λΈλ‘κ·Έμ title, description, author, siteUrl, ogImage, social μ λ³΄λ₯Ό μλ ₯ν©λλ€. (**title**μ λΈλ‘κ·Έ μλ¨μ λ³΄μ΄λ λΈλ‘κ·Έ μ΄λ¦μ λνλλλ€.)

```js
module.exports = {
    title: '', // zoomkoding.dev
    description: '', // μ€μ½λ©μ κ°λ°μΌκΈ°
    author: '', // zoomkoding

    siteUrl: '', // https://gatsby-starter-zoomkoding.netlify.com
    ogImage: '', // κ³΅μ ν  λ λ³΄μ΄λ λ―Έλ¦¬λ³΄κΈ° μ΄λ―Έμ§
    social: {
        github: '', // https://github.com/zoomKoding
        linkedIn: '', // https://www.linkedin.com/in/jinhyeok-jeong-800871192
        email: '', // zoomkoding@gmail.com
    },
    ...
}
```

### 2. bio

**bio**λ ννμ΄μ§μ κΈμ΄μ΄λ₯Ό μκ°νλ μΉμμμ μ¬μ©λ©λλ€. νμ¬ μμ΄μ νκ΅­μ΄ λκ° λ€ μ§μμ ν©λλ€. 
**description**μ μμ μ μ€λͺνλ λ¬Έκ΅¬λ₯Ό μ¬λ¬κ° λ£μ μ μμ΅λλ€. bioμμ μ¬μ©νλ **λ―Έλͺ¨μ§λ₯Ό μμ **νκ³  μΆλ€λ©΄ `src/assets/author.mp4`μ λμμμ μ½μνλ©΄ λ©λλ€.

> π€ μΈμ΄μ λ°λΌ descriptionμ ν¬λ§·μ΄ λ¬λΌμ§λ λ§μμ λμλ ννμ λ§κ² descriptionμ μμ±ν΄μ£ΌμΈμ. 


```js
module.exports = {
    ...

    bio: {
        language: 'ko', // ko, en μ ν κ°λ₯(μμ΄ μ νμ μ΄μμ΄ λ³κ²½λ©λλ€.)
        name: '', // μ€μ½λ©
        description: ['μ΄λ‘μ΄ κ²μ λ§λλ', 'λ°°μμ μ’μνλ', 'κΈλ‘ λλκΈΈ μ’μνλ'],
    },
    ...
}
```

### 3. comments

**comments**λ ν¬μ€νμ λκΈ κΈ°λ₯μ μ κ³΅ν  μλΉμ€μ μ λ³΄λ₯Ό λ°μ΅λλ€. νμ¬λ github κ³μ μΌλ‘ λκΈμ μμ±ν  μ μλ utterancesλ§ μ§μν©λλ€.

> π¦ utterances μ¬μ©λ°©λ²μ [λ§ν¬](https://utteranc.es/)λ₯Ό μ°Έκ³ ν΄μ£ΌμΈμ!

```js
module.exports = {
    ...

    comments: {
        utterances: {
            repo: '' // zoomkoding/gatsby-starter-zoomkoding
        },
    },
    ...
}
```

## π€ about page λ§λ€κΈ°
about νμ΄μ§ λν gatsby-meta-config.jsλ₯Ό ν΅ν΄ μμ±λ©λλ€. about νμμ μλ timestampsμ projectsμ κ°κ° μ λ³΄λ₯Ό μλ ₯νμλ©΄ about νμ΄μ§κ° μλ μμ±λ©λλ€.

### 1. timestamps

μλμ κ°μ΄ κ° timestamp μ λ³΄λ₯Ό λ°°μ΄λ‘ μ κ³΅ν΄μ£Όμλ©΄ μλ ₯νμ  μμμ λ§μΆ°μ timestamps sectionμ λ³΄μ¬μ§κ² λ©λλ€.

> linksμ ν΄λΉ μ λ³΄κ° μλ€λ©΄ μλ΅ν΄λ λ©λλ€.

```js
module.exports = {
    ...

    about: {
        timestamps: [
            {
                date: '', // κΈ°κ°
                activity: '', // νλ
                links: { // λ§ν¬κ° μλ€λ©΄ μ§μ°μλ λ©λλ€.
                    post: '', // λΈλ‘κ·Έ ν¬μ€ν λ§ν¬
                    googlePlay: '', // κ΅¬κΈνλ μ΄ λ§ν¬
                    appStore: '' // μ±μ€ν μ΄ λ§ν¬
                    github: '' // κΉνλ§ν¬
                },
            }
            ...
        ],
        ...
    },
    ...
}
```

### 2. projects
λ§μ°¬κ°μ§λ‘ κ° project μ λ³΄λ₯Ό λ°°μ΄λ‘ μ κ³΅ν΄μ£Όμλ©΄ μλ ₯νμ  μμμ λ§μΆ°μ projects sectionμ λ³΄μ¬μ§κ² λ©λλ€.

```js
module.exports = {
    ...

    about: {
        ...

        projects: [
            {
                title: '', // νλ‘μ νΈ μ λͺ©,
                description: '', // μ€λͺ,
                techStack: ['flutter', 'nodejs'], // κΈ°μ  μ€ν
                thumbnailUrl: '', // μΈλ€μΌ μ΄λ―Έμ§ μ£Όμ
                links: { // λ§ν¬κ° μλ€λ©΄ μ§μ°μλ λ©λλ€.
                    post: '', // λΈλ‘κ·Έ ν¬μ€ν λ§ν¬
                    googlePlay: '', // κ΅¬κΈνλ μ΄ λ§ν¬
                    appStore: '' // μ±μ€ν μ΄ λ§ν¬
                    github: '' // κΉνλ§ν¬
                },
            },
            ...
        ],
        ...
    },
    ...
}
```

<br/>

κ·Έλ κ² λ΄μ©μ λ¬Έμ  μμ΄ μλ ₯νμ¨λ€λ©΄ λλ§μ λΈλ‘κ·Έκ° νμν κ²μ νμΈνμ€ μ μμ΅λλ€.π

> λ³λμ¬ν­μ μ€ν μ€μΈ λΈλ‘κ·Έμμ νμΈνμλ €λ©΄ `npm start`λ₯Ό ν΅ν΄ μ¬μ€νν΄μ£ΌμΈμ!

## βοΈ κΈ μ°κΈ°

λ³Έκ²©μ μΌλ‘ λΈλ‘κ·Έμ κΈμ μ°λ €λ©΄ `/content` μλμ λλ ν λ¦¬λ₯Ό μμ±νκ³  `index.md`μ markdownμΌλ‘ μμ±νμλ©΄ λ©λλ€.
> μ΄ λ, ν΄λμ μ΄λ¦μ κ²½λ‘λ₯Ό μμ±νλλ° λ©λλ€. 

### βΉοΈ λ©ν μ λ³΄

index.md νμΌμ μλ¨μλ μλμ κ°μ΄ emoji, title, date, author, tags, categories μ λ³΄λ₯Ό μ κ³΅ν΄μΌ ν©λλ€.
> emojiλ κΈλ¨Έλ¦¬μ λ³΄μ¬μ§κ² λλ©°, categoriesλ λμ΄μ°κΈ°λ‘ λλμ΄ μ¬λ¬κ°λ₯Ό μλ ₯ν  μ μμ΅λλ€.

```
---
emoji: π§’
title: Getting Started
date: '2021-03-22 23:00:00'
author: μ€μ½λ©
tags: tutorial
categories: tutorial
---
```

### πΌ μ΄λ―Έμ§ κ²½λ‘

κΈμ μ΄λ―Έμ§λ₯Ό μ²¨λΆνκ³  μΆμΌμλ€λ©΄ κ°μ λλ ν λ¦¬μ μ΄λ―Έμ§ νμΌμ μΆκ°νμμ μλμ κ°μ΄ μ¬μ©νμλ©΄ λ©λλ€.

```
![μ¬μ§](./[μ΄λ―Έμ§ νμΌλͺ])
```

### π λͺ©μ°¨ μμ±

κΈμ μ°μΈ‘μ λͺ©μ°¨κ° λ³΄μ΄κΈ°λ₯Ό μνμ λ€λ©΄ `index.md` νμΌ λ§¨ μλμ λ€μ λ΄μ©μ μΆκ°νμλ©΄ μλμΌλ‘ λͺ©μ°¨κ° μμ±λ©λλ€.

    ```toc
    ```
