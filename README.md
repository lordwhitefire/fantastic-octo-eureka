<!DOCTYPE HTML>
<html>
  <head>
<meta charset="UTF-8">
    <style>
.button {
  display: inline-block;
  border-radius: 4px;
  background-color: red;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
  box-shadow: 0px 9px gray;
  opacity: 0.5;
}

   .button span {
cursor :pointer;
  display: inline-block;
  position:relative;
  transition :0.5s;
    }
.button span:after {
content: "\01F602";
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}
.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: -20px;
}
.button:active{
  transform: translateY(4px);
}
.button:hover {
  opacity: 1;
}
    </style>
    </head>
    <body>
      <h2>animated image</h2>
      <button class="button"><span> hover</span> </button>

      </body>
      </html>
