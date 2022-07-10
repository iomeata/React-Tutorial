# React-Tutorial

React-Tutorial by Ifeanyi Omeata

## Tutorial

---

### [1-JAVASCRIPT BASICS](#)

---

<!--
<details>
  <summary>OPEN</summary>
<hr> -->

<details>
  <summary>1. Arrow Functions</summary>

```Javascript
const name = "Ifeanyi";
console.log(name)

const printMyName = (name) => {
  console.log(name);
}

const multiply = number => number * 3;

printMyName("Bob");
console.log(multiply(4));
```

</details>

<details>
  <summary>2. Exports and Imports Defaults</summary>

With Default:

```Javascript
const person = {
  name: "Ifeanyi",
  age: 23,
  hobbies: ["Reading", "Coding", "Gaming"]
}

export default person;
```

```Javascript
import person from "./person.js";
import prs from "./person.js";
```

Without Default:

```Javascript
export const clean = () => {
  console.log("Cleaning");
}

export const cook = () => {
  console.log("Cooking");
}
```

```Javascript
import { clean, cook } from "./activities.js";
import { clean as cleanHouse, cook as cookFood } from "./activities.js";
import * as activitiesObject from "./activities.js";
```

</details>

<!-- <details>
  <summary>6. Add Django Rest Framework and App to settings</summary>

[here](https://github.com/iomeata/Django-API-Tutorial-1/commit/388d9ef90e787e6836b472370251500993521611)

```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'rest_framework',
    'quickstart',
]
```

</details> -->
<!--
</details> -->

---

### [2-SERIALIZATION](#)

---

<details>
  <summary>1. Install pygments</summary>

```python
pip install django
pip install djangorestframework
pip install pygments  # We'll be using this for the code highlighting
```

<!-- <details>
  <summary>3. Create snippets model</summary>

```python
python manage.py startapp snippets
```

</details>

<details>
  <summary>4. Create a virtual environment</summary>

</details> --> -->
