body {
  background-color: black;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -ms-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -o-user-select: none;
  user-select: none;
  font-family: monospace;
  font-weight: bold;
  color: #ffffff;
  text-shadow: 1px 1px 1px rgba(0,0,0,100), 1px 1px 1px rgba(0,0,0,100);
}
pre {
  text-align: center;
  font-family: monospace;
}
p {
  text-align: center;
  font-family: monospace;
}
#center {               
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);    
  -webkit-transform: translate(-50%, -50%);
  -moz-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  -o-transform: translate(-50%, -50%);
}
a {
    color: inherit;
    text-decoration: none;
}
video {
  position: fixed;
  top: 50%;
  left: 50%;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: -100;
  transform: translateX(-50%) translateY(-50%);
  background-size: cover; 
  -webkit-filter: blur(125px);
  -moz-filter: blur(125px);
  -o-filter: blur(125px);
  -ms-filter: blur(125px);
  filter: blur(0px);
}
