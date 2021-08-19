# restAPI

This is a postman collection against Dummy API https://reqres.in/
The script contains requests such as GET, PUT, POST & DELETE. 

How to run:

Simply clone or download the json file, and import it in Postman. Then run the entire collection. 

To run the HTML Report, you need to integrate Postman Newman HTML report. 

Use this command to install newman-html reporter: $ npm install -g newman-reporter-html

And then run the collection using this command: newman run <collection Directory> -r html
