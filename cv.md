# Atamanyuk Alexander

## Contact Information

* **Socials**
    + telegram: @acidmange
    + linkedln: [link](https://www.linkedin.com/in/alexander-atamanyuk-b7676b29a)  
* **Others**
    + email: psotiframe13@gmail.com
    + phone: +79222135701

## About

Currently I work as a system administrator in a construction company. My goals are to expand my knowledge in computer science and gain a deep understanding of web technologies. I strive to become a competent fullstack developer. Thats why I finished a layout designer course on hexlet.io, and now I’m taking the frontend-developer course at rsschool

## Skills

* HTML
* CSS (BEM, Bootstrap, Sass, Adaptive Design)
* JavaScript (Jest, Gulp, Pug)
* Git
* Figma
* Surge
* NodeJS

## Code Example 

**Description:**

Implement and export by default a function that takes as input an array of a certain structure and returns an object derived from that array

**Example**

```javascript
convert([]); // {}
convert([['key', 'value']]); // { key: 'value' }
convert([['key', 'value'], ['key2', 'value2']]); // { key: 'value', key2: 'value2' }

convert([
  ['key', [['key2', 'anotherValue']]],
  ['key2', 'value2']
]);
// { key: { key2: 'anotherValue' }, key2: 'value2' }
```

**Code**

```javascript
const convert = (arr) => arr.reduce((acc, [key, value]) => {
  if (!Array.isArray(value)) {
    acc[key] = value;
  } else {
    acc[key] = convert(value);
  }
  return acc;
}, {});

export default convert;
```

## Courses

* **Hexlet - Layout Design** (Completed)

![Hexlet Layout Design course](/assets/images/hexlet.png)

* **RSSchool - Frontend Developer** (In progress)

## Projects

* [**Hexlet Frontend project**](https://github.com/acidmange/frontend-project-lvl1)
* [**Hexlet Layout Design project**](https://github.com/acidmange/layout-designer-project-56)
* [**NodeJS Basics Project**](https://github.com/acidmange/node-nodejs-basics/tree/nodejs-basics)
* [**NodeJS File Manager**](https://github.com/acidmange/node-file-manager/tree/file-manager)
* [**Shelter Frontend Project**](https://github.com/acidmange/RSSchool-Shelter/tree/main)

## Languages

![Efset Certificate](/assets/images/efset.png)

* **English** (Proficient)
    + [EFSET Certificate](https://www.efset.org/cert/nXSVsY)
* **Russian** (Native)
