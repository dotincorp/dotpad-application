# Dot Middleware for Kiosk

## Download
#### Download by version
- 3.0.1 : <a href="dot-middleware-kiosk-3.0.1.zip">download</a> (2023.10.25) : Add a rest api
- 3.0.0 : <a href="dot-middleware-kiosk-3.0.0.zip">download</a> (2023.04.11) : Add administrator privileges at runtime

#### How to download
 - Click the link for the file version you want to download.  
 - Click the Download button.  
   <img src="images/download.gif" alt="How to download">

 ## Kiosk Elements
 - Middleware program
   <img src="images/program.gif" alt="Run program">

- 300 cell device  
  <img src="images/device-300cell.png" alt="300 cell device" width="600">

- 20 cell device  
  <img src="images/device-20cell.png" alt="20 cell device" width="600">

## REST API usage guide
### print to a 300 cell device
- API information : <a href="sample.dtm">downlaod sample.dtm</a>  
  ```
    URL (POST) : http://127.0.0.1:8291/request/111
    Parameter(JSON) : {"DTM_FILE_PATH": "D:/Data/dtm/ample.dtm"}
  ```

- Post Man  
  <img src="images/postman-300cell.gif" alt="Post Man 300cell">

### print to a 20 cell device  
- API information
  <a href="sample.dtm">downlaod sample.dtm</a>
  ```
    URL (POST) : http://127.0.0.1:8291/request/111
    Parameter(JSON) : {"DTM_FILE_PATH": "D:/Data/dtm/ample.dtm"}
  ```

- Post Man  
  <img src="images/postman-300cell.gif" alt="Post Man 300cell">


