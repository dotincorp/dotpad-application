# Dot Middleware for Kiosk

## Download Link
- 3.0.1 : <a href="dot-middleware-kiosk-3.0.1.zip">download</a> (2023.10.25) : Add a rest api
- 3.0.0 : <a href="dot-middleware-kiosk-3.0.0.zip">download</a> (2023.04.11) : Add administrator privileges at runtime

## How to download
 - Click the link for the file version you want to download.  
 - Click the Download button.  
   <img src="images/download.gif" alt="How to download">

 ## Kiosk Elements
 <details>
    <summary>Middleware program</summary>  
    <pre>
      <img src="images/program.gif" alt="Run program">
    </pre>
  </details>
  <details>
    <summary>300 cell device</summary>  
    <pre>
      <img src="images/device-300cell.gif" alt="300 cell device">
    </pre>
  </details>
  <details>
    <summary>20 cell device</summary>  
    <pre>
      <img src="images/device-20cell.gif" alt="20 cell device">
    </pre>
  </details>

## REST API usage guide
  <details>
    <summary>API to print to a 300-cell device</summary>  
    <pre>
       <li> api </li>
       <a href="sample.dtm">downlaod sample.dtm</a>
       <code>
         URL (POST) : http://127.0.0.1:8291/request/111
         Parameter(JSON) : {"DTM_FILE_PATH": "D:/Data/dtm/ample.dtm"} 
        </code>
      <li>post-man</li>
      <img src="images/postman-300cell.gif" alt="Post Man 300cell">
    </pre>
    
  </details>
  <details>
    <summary>API to print to a 20-cell device</summary>  
    <pre><code>
      URL (POST) : http://127.0.0.1:8291/request/111
      Parameter(JSON) : {"DTM_FILE_PATH": "D:/Data/dtm/1_1_A.dtm"} 
    </code></pre>
    <img src="images/postman-20cell.gif" alt="Post Man 200cell">
  </details>
