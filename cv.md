# Konstantin Yurchenko

## **Contact Information:**  
+ **Email:** <u>[kostyayurchenko84@gmain.com](https://workspace.google.com/intl/ru/gmail/)</u>
+ **Phone:** _+375294162201_
+ **Github:** <u>[kostyayurchenko84](https://github.com/kostyayurchenko84)</u>

---

## About Me
_I am an engineer, that wants to learn and grow in the field of programming. I have got analytical skills, responsibility, quick to adapt, diligence. Now, I have a basic foundation in web development, I haven't worked in any development project.. I am committed to continuous learning and trying to apply new knowledge practically._

---

## Skills
+ **Delphi**, **JavaScript**, **HTML**, **CSS**  
+ **React.js**, **Node.js**  
+ **GitHub**  
+ **VS Code**, **DBveawer**, **Docker**

---

## Code Examples
### React Function:
```typescipt
import crypto from 'crypto'
import { env } from '../lib/env'

export const getPasswordHash = (password: string) => {
  //console.info(password)
  //console.info(crypto.createHash('sha256').update(password).digest('hex'))
  return crypto.createHash('sha256').update(`${env.PASSWORD_SALT}${password}`).digest('hex')
}
```

### Other React Function:
```typescipt
    <button
      className={css.likeButton}
      onClick={() => {
        void setIdeaLike.mutateAsync({ ideaId: idea.id, isLikedByMe: !idea.isLikedByMe })
      }}
    >
      {idea.isLikedByMe ? 'Unlike' : 'Like'}
      <Icon size={32} className={css.likeIcon} name={idea.isLikedByMe ? 'likeEmpty' : 'likeFilled'} />
    </button>
```

---

## Work Experience / Projects
**Meals shop (Educational Project)**  
Skills used: React, HTML, CSS, JavaScript, SQL  
Created a responsive website to order meals.

**Meeting Management App (Educational Project)**  
Skills used: React.js, JavaScript, HTML, CSS, SQL
Built a simple meeting management application allowing users to add, edit, and delete events. 

**IdeaNick website (Educational Project)**  
Skills used: JavaScript, React, CSS, Prisma, SQL, Github
Developed a react app for adding and storing excellent ideas ).

---

## Education
+ ** Belorussian state univercity of transport **, Gomel, Belarus, 2007
+ ** React - The Complete Guide 2025 (incl. Next.js, Redux) (Udemy) **, 2025
+ ** Full-stack web service development from scratch using TypeScript, React, Node.js **, 2025
+ ** Java Fullstack (Javarush) **,2021

---

## Languages
**English:** Intermediate (B1). I practice reading technical articles and watching tutorials in English regularly. I can understand technical documentation.  
