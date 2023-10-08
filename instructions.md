## Instructions

<div align="left">
<img src="green_light_logo.jpg" width="200" height="500" alt="Glossary logo">
</div>


## Contents

+ [Node.js](#node-js)<br>
+ [GitHub helpful](#github-helpful)<br> 

<br>
<br>
<br>

<h2 id="github-helpful">GitHub helpful</h2>

#### Markdown GItHub user (RU) 
This is the *[Markdown Cheatsheet](https://github.com/sandino/Markdown-Cheatsheet/tree/master#%D1%88%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0-%D0%BF%D0%BE-markdown)*

#### Markdown from GitHub base (ENG) 
This is the *[Markdown Guide base](https://www.markdownguide.org/basic-syntax/#overview)*

#### Markdown from GitHub Extended Syntax (ENG) 
This is the *[Markdown Guide Extended Syntax](https://www.markdownguide.org/extended-syntax/#overview)*

<br>
<br>
<br>

<h2 id="node-js">Node.js</h2>

### Node npm helpful packages.
Node.js is an open-source, cross-platform, JavaScript runtime for writing servers and command-line tools<br>
*[see packages](https://github.com/sindresorhus/awesome-nodejs)* <br>
or <br>
need write in adress string browser chrome this<br>
```javascript
node.cool

```
<br>

### Package.json
How to use [package.json](https://habr.com/ru/companies/domclick/articles/510812/)

<br>

**Инициализация проекта:**
```javascript
npm init
```
(интерактивно)
```javascript
npm init -y
```
(с последующим редактированием в IDE)
<br>
**Добавление зависимостей:**
```javascript
npm install <dependency>

npm install <dependency-1> <dependency-2>…

npm install -D <dev-dependency>…
```
<br>

**Проверка и обновление зависимостей:**
```javascript
npm outdated
```
(просмотр прямых устаревших зависимостей)
```javascript
npm outdated --depth=9999
```
(просмотр всех устаревших зависимостей)
```javascript
npm update
```
(обновление прямых устаревших зависимостей с учетом semver)
```javascript
npm update --depth=9999
```
(обновление всех устаревших зависимостей с учетом semver)
```javascript
npm-check
```
(просмотр прямых устаревших зависимостей)
```javascript
npm-check -u
```
(интерактивное обновление прямых устаревших зависимостей)
<br>

**Удаление зависимостей:**
```javascript
npm rm <dependency>
```
