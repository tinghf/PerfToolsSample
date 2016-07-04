### Exploration Anaylsis for the Capstone Dataset

### Background

In this capstone project we attempt to build a predictive test models like those used by SwiftKey. This report contains the exploratory analsys of the dataset provided by coursera.

### Problem Statement 
*Performance Tool Problem*
A RESTful web service defines the following protocol for uploading a large file (based on Amazon’s S3 multipart upload API):
1. POST /ObjectName?uploads  
    No body content.
2. PUT /ObjectName?partNumber=PartNumber&uploadId=UploadId  
    The body contains the content of the part.
3. POST /ObjectName?uploadId=UploadId  
    No body content.
 
Design and implement a program that benchmarks performance characteristics of the RESTful web service.
- Clearly define which performance benchmarks should such a tool focus on and what it shouldn’t.
- Also provide your thinking behind what the various inputs & outputs the tool will have.



### Solution Source files 

| Name                      | Description                                                      |
| ------------------------- | -----------------------------------------------------------------|
| readme.1st                | readme file for the solution with design overview
| CommandLineParser/*.cs    | command line parsing util for the executable tool ;              |
| ConsoleApplicaiton1/*.cs  | entry point for benchmarkt tool executable plus some simpple statistics extension;    |


