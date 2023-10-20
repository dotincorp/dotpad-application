# Dot Middleware User

## Download Link
- 1.0.2-beta <a href="dot-middleware-user-1.0.2-beta.zip">download</a> (2023.10.19) : Added http server method
- 1.0.1-beta <a href="dot-middleware-user-1.0.1-beta.zip">download</a> (2023.10.01) : Modified device status management
- 1.0.0-beta <a href="dot-middleware-user-1.0.0-beta.zip">download</a> (2023.09.26) : First version added

## How to download
 - Click the link for the file version you want to download.  
 - Click the Download button.  
   <img src="images/download.gif" alt="How to download">

## User manual
  <details>
    <summary>Add Dot Pad</summary>
    <img src="images/middleware.gif" alt="Dot Middleware">
  </details>

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
