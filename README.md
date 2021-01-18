<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Hello World with React</title>
  </head>
  <body>
    
<div id="like_button_container">
</div>

  <script src="https://unpkg.com/react@17/umd/react.development.js" crossorigin>
  </script>
  
  <script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js" crossorigin>
  </script>
  
  <script src="like_button.js">
  </script>

const domContainer = document.querySelector('#like_button_container');
ReactDOM.render(e(LikeButton), domContainer);




  </body>
</html>
