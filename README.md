# comp2068-presentation-final

# 1. What is file upload
  - File upload is the transmission of a file from local computer to server computer.
  - File upload takes place using FTP, HTTP, HTTPS, SOAP, and etc protocols.
  - In http protocol, we need to use multipart uploading, we will use "multer" npm module.
  
# 2. How to upload file
  - First, save binary file into database directly.
  - Second, save file into server computer and save the link in database
  - Third, save binary file into commercial other server site and save the link in database.
  
  - We will use second way to upload file.

# 3. Demonstration (In the class)