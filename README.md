# Web Dev Class

Hello friends



# First Day

We learned:
- Using VS Code to create an `index.html` file
- HTML Tags
    - The `<h1>` tag
    - The `<h2>` tag
    - The `<h3>` tag
    - The `<p>` tag
    - The `<img>` tag
- Some basic CSS

Your `index.html` file should look something like this

```html
<head>
  <style>
    h1 {
      color: red;
    }
  </style>
</head>

<body>
  <h1>Mr. Tyhacz's Class</h1>
  <h2>We are cool</h2>
  <h3>February 9, 2023</h3>
  <p>
    This is a paragraph
  </p>
  <img src="filename.jpg" width="200">
</body>
```

# Second Day

We are looking into tables! Tables are used to show lots of standardized data at once.


### Step 1

- Start with the open and close `<table>` tags
- Leave a couple empty lines between them for room.

```html
<table>

</table>
```

### Step 2

- The `<tr>` tag stands for `t`able `r`ow. 
- Let's add one `<tr>` _inside_ our `<table>`

```html
<table>
  <tr></tr>
</table>
```

### Step 3

- We have declared our rows - now we need columns.
- We first have to add our `t`able `h`eaders with the `<th>` tag like this:

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
</table>
```

### Step 4

- Now that our table headers are defined, let's add rows of our data!
- `<th>` is only used in the **FIRST** row.
- For our data columns, we use `t`able `d`ata tags - `<td>` like this:

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>Noah</td>
    <td>13</td>
    <td>Wilmington</td>
  </tr>
  <tr>
    <td>Jacob</td>
    <td>13</td>
    <td>Wilmington</td>
  </tr>
  <tr>
    <td>Daniel</td>
    <td>10</td>
    <td>Wilmington</td>
  </tr>
</table>
```
