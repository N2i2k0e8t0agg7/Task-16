# Student Search Application
## Overview
This project is a simple student search application built using:
- HTML
- CSS
- JavaScript
The application displays student cards dynamically using JavaScript `map()` and filters the data using `filter()`.
Users can search students by name using the search bar.

# Features
- Dynamic card generation using `map()`
- Search functionality using `filter()`
- Case-insensitive search
- Responsive grid layout
- Sticky navbar and search section
- DOM manipulation using JavaScript

# JavaScript Workflow
## Step 1: Store Student Data
```js
const data = [
   {
      name: "Niket",
      class: "12th",
      marks: "91%",
      address: "India"
   }
]
```

## Step 2: Generate Cards Using `map()`
```js
const boxes = data.map((inst) => {
    return box;
});
```

## Step 3: Display Cards
```js
ins.append(...boxes);
```
Spread operator (`...`) is used to append all cards together.

## Step 4: Search Functionality
```js
search.addEventListener("click", () => {

});
```

## Step 5: Filter Matching Names
```js
newarr = data.filter((inst) => {
    return inst.name.toLowerCase().includes(q.toLowerCase());
});
```

This allows partial search.
Examples:
- `e` → shows all names containing `e`
- `ni` → shows `Niket`

# Important Learnings

## Difference Between `map()` and `forEach()`
| Method | Purpose |
|---|---|
| `map()` | Returns a new array |
| `forEach()` | Executes code for each item |
| `filter()` | Returns matching items |

# Output
The application:
- Shows all student cards initially
- Filters students on search
- Dynamically updates UI without page reload

# Author

Created by Niket as a JavaScript Map & Filter Assignment project.
