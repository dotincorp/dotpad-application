# Dot Middleware User (MacBook)

## Download Link
- 1.0.3-beta <a href="https://github.com/dotincorp/dotpad-application/raw/refs/heads/main/Dot%20Middleware/Dot%20Middleware%20User/MacBook/dot-middleware-user-1.0.3-beta.dmg">download</a> (2025.04.18) : Fixed instability in Dotpad connection/reconnection


## Install
- Run the installation file
<img src="images/install-step1.png" alt="Run the installation file">

- Privacy and Security Settings
<img src="images/install-step2.png" alt="Privacy and Security Settings">

## API usage
  <details>
    <summary>Dot Pad print API</summary>  
    <pre><code>
      URL (POST) : http://127.0.0.1:8291/send
      Parameter(JSON) : {"SENDER":"CANVAS","TYPE":"PRINT_DOTPAD","MESSAGE":"Tactile hex data to be printed on 300 cells"}  
    </code></pre>
    <img src="images/postman.gif" alt="Post Man">
  </details>
  
  <details>
    <summary>Dot Pad print  </summary>  
    <img src="images/dotpad.jpg" alt="Dot Pad Print">
  </details>    
