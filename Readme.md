
# brewster-form

  Really basic (incomplete) form based on the [brewster](https://www.brewster.com/) iphone app.

  ![brewster-form](http://f.cl.ly/items/181D0X2t2h0E0J2X0z1X/Screen%20Shot%202012-11-19%20at%201.27.44%20PM.png)

## Installation

    $ component install matthewmueller/brewster-form

## Example

```html
<form class="brewster" action="/signup" method="post">
  <div class="field">
    <label for="__username">username</label>
    <input name="username" type="text" id="__username">
    <span class="validation valid"></span>
  </div>
  <div class="field">
    <label for="__email">email</label>
    <input name="email" type="text" id="__email">
    <span class="validation valid"></span>
  </div>
  <div class="field">
    <label for="__password">password</label>
    <input name="password" type="password" id="__password">
    <span class="validation invalid"></span>
  </div>
</form>
```

## License

  MIT
