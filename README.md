# Paper User Picture
`paper-userpicture-custom` lets you create user avatars. If user doesn't have picture set, we'll automatically create placeholder containing user name initials.


## Styling
Custom property | Description | Default
----------------|-------------|----------
`--paper-userpicture-custom-size` | The size of picture | `5em`
`--paper-userpicture-custom-text-size` | The font-size of the placeholder initials |
`--paper-userpicture-custom-text-color` | The custom text color  |

 `calc(var(--paper-userpicture-custom-size) / 2)`

## Demos
### Basic example
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-userpicture-custom.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <style>body{font-family:'Roboto'}.users{display:flex;}.users paper-userpicture-custom{flex:1;}</style>
    <div class="users">
        <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<paper-userpicture-custom user-id="AAA" user-name="Petja"></paper-userpicture-custom>
<paper-userpicture-custom user-id="BBB" user-name="Oliver"></paper-userpicture-custom>
<paper-userpicture-custom user-id="CCC" user-name="Luke"></paper-userpicture-custom>
<paper-userpicture-custom user-id="DDD" user-name="Yusef"></paper-userpicture-custom>
```

### Show names under pictures
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-userpicture-custom.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <style>body{font-family:'Roboto'}.users{display:flex;}.users paper-userpicture-custom{flex:1;}</style>
    <div class="users">
        <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<paper-userpicture-custom user-id="EEE" user-name="Henry"></paper-userpicture-custom>
<paper-userpicture-custom user-id="FFF" user-name="Thomas"></paper-userpicture-custom>
<paper-userpicture-custom user-id="GGG" user-name="Michael"></paper-userpicture-custom>
<paper-userpicture-custom user-id="HHH" user-name="Leo"></paper-userpicture-custom>
```

### Use real user picture
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-userpicture-custom.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <style>body{font-family:'Roboto'}.users{display:flex;}.users paper-userpicture-custom{flex:1;}</style>
    <div class="users">
        <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<paper-userpicture-custom image="http://lorempixel.com/160/160?1" user-id="III" user-name="Henry"></paper-userpicture-custom>
<paper-userpicture-custom image="http://lorempixel.com/160/160?2" user-id="JJJ" user-name="Thomas"></paper-userpicture-custom>
<paper-userpicture-custom image="http://lorempixel.com/160/160?3" user-id="KKK" user-name="Michael"></paper-userpicture-custom>
<paper-userpicture-custom image="http://lorempixel.com/160/160?4" user-id="LLL" user-name="Leo"></paper-userpicture-custom>
```
