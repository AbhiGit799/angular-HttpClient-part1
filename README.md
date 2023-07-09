# angular-HttpClient-part1

Hi, <br/>

This is a simple Angular POC created by Abhishek Choubey. <br/>

In this POC I tried to demonstrate HttpClient in Angular. <br/>

Here, <br/>

I used HttpClient get() and used different optional parameters of <br/>

HttpClient get() <br/>
 
HttpClient.get accepts URL and other options such as parameter, headers etc. HttpClient.get has  <br/>
following options to request http GET method. <br/>

<b>headers:</b> It is of HttpHeaders types. It sets headers for the http GET request. <br/>

<b>observe:</b>  It defines whether we want complete response or body only or events only. We need to assign values for  <br/>
observe property such as response for complete response, body for response with body and events for response  <br/>
with events. <br/>

<b>params:</b>  It is of HttpParams type. It sets parameters in URL for http GET request. <br/>

<b>reportProgress:</b>  It is of boolean type. It is useful when we are requesting data. Setting reportProgress value as true  <br/>
we can know progress report for our HttpClient.get request. <br/>

<b>responseType:</b>  It is used to define response type of HttpClient.get request. Its values can be arraybuffer, blob, json  <br/>
and text. <br/>

<b>withCredentials:</b>  It is of boolean type. If the value is true then HttpClient.get will request data with credentials. <br/>


Software Used <br/>
node --version = v14.20.0 <br/>
npm --version = 6.14.17 <br/>
ng version <br/>
Angular CLI: 14.0.0 <br/>

Check my work 👉👉👉👉 https://abhigit799.github.io/angular-HttpClient-part1/


<br/>
