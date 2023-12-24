<h2>Form Validator</h2>

Step 1 - HTML

- Edit the title of the html file to `form validator`
- Link to the style sheet `style.css`
- Add the `app.js` to the html file
- Create a div with a class of container `.container`
- Create a form in the conanter claas with `id="form"`, `class="form"`
- Create a `h2` tag with content `Register with us`
- Create a div `.form-control`
- Inside the `.form-control` div place the following:
  - A label called username with the attribute `for="username"`
  - An input with `type="text"`, `id="username"` and `placeholder="Enter username"`
  - A small tag with the text `Error message`

```js
<div class="form-control">
    <label for="username">Username</label>
    <input type="text" id="username" placeholder="Enter uername">
    <small>Error message</small>
</div>
```

- Copy the `.form-control` div, three times
- Edit the divs, as sgown bellow:

```js
<div class="form-control">
    <label for="email">Email</label>
    <input type="text" id="email" placeholder="Enter email">
    <small>Error message</small>
</div>
<div class="form-control">
    <label for="password">Password</label>
    <input type="password" id="password" placeholder="Enter password">
    <small>Error message</small>
</div>
<div class="form-control">
    <label for="password2">Confirm Password</label>
    <input type="password" id="password2" placeholder="Enter password again">
    <small>Error message</small>
</div>
```

- Add a button `Submit`
