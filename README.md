<h1>API Testing Project for **OMDbAPI**</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.
THe OMDb API is an API where you can view, insert or obtain movie information, all content and images from an movie database.<br>
Application under test: **OMDbAPI**

4</h4><strong>Tools used: Postman.<strong>4</h4>

In the Authorization section, it will be used for each test an API Key: d0236222

Collection link: **https://www.omdbapi.com/**

</h2>**Tests performed**</h2>


**Find OMDb API**

HTTP method for request: **GET**<br>
Request description: **Search the URL for verification**<br>
Test types / techniques used: **Functional Testing**<br>
Response status code: *200 OK**<br>

![image](https://github.com/user-attachments/assets/5807ceeb-9d18-4375-a99b-ace455fce173)

JavaScript Tests:

![image](https://github.com/user-attachments/assets/a8e4fd71-3f3d-4aa1-b91d-9c3c8b98a5ec)

<li>**Fake API Key**</li>

HTTP method for request: **GET**<br>
Request description: **I inserted an invalid API key to check the server's functionality**<br>
Test types / techniques used: **Security Testing**<br>
Response status code: *401 Unauthorized***<br>


![image](https://github.com/user-attachments/assets/278bb205-7fef-4e9e-8823-fe36bd3b6825)
<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/500636a5-34ed-44de-b513-4f3c644e86ca)
<br>



**Find by title**

HTTP method for request: **GET**<br>
Request description: **Search for the movie by title in IMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>


![image](https://github.com/user-attachments/assets/6e2f137d-b287-41f6-b24b-de32373111e8)
<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/097f5b0c-0845-4820-8968-0fb22471789d)
<br>

**Find by ID**

HTTP method for request: **GET**<br>
Request description: **Search for the movie by ID in IMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/64ce86c8-1161-48f4-abd1-be68a8148bcb)

<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/86c49acd-ed95-4602-b3a9-322919c920ab)
<br>

**Find by Title and ID**

HTTP method for request: **GET**<br>
Request description: **Search for the movie by Title and ID in IMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/494ff912-a8ec-48d6-8683-2c03a7b887ee)
<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/d1f0733a-d4b4-46f4-9421-eed191edd367)

**Find a Poster from a movie**

HTTP method for request: **GET**<br>
Request description: **Search for a poster from a movie you found earlier in IMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/5a5db192-80f1-4390-a566-daf1caab39a5)
<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/3058f6ac-a960-4ddd-add1-9604f989ca6e)

<br>

**Post movie**

HTTP method for request: **POST**<br>
Request description: **Post a new movie in OMDb from IMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/8a9d5444-1d99-40b8-82e9-cb04cda4dc2c)

<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/5de7d30f-f563-470a-900f-25219556a638)

<br>

**Find the new movie**

HTTP method for request: **GET**<br>
Request description: **Search for the new movie by ID in OMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/03324ec0-bbf4-4c62-b1df-bfcf3e100774)

<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/e4d7aa91-c1da-4140-b1bd-4ea6f8514686)

**Post a Poster for the new movie**
HTTP method for request: **POST**<br>
Request description: **I posted a poster for the new movie in OMDb**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/afe15113-04ad-4110-a7b5-f674a867e23b)

<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/762b2e64-106e-4e36-b046-1818c44b79f5)
<br>

**Post an invalid movie**

HTTP method for request: **POST**<br>
Request description: **I tried to post a movie that doesn't exist**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **200 OK**<br>

![image](https://github.com/user-attachments/assets/95739166-1d5f-4d08-a9d5-12d7351edde2)
<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/eeb1b726-3e98-4ba7-81aa-4c12216245ea)



<br>

**Delete the poster**

HTTP method for request: **DELETE**<br>
Request description: **I tried to delete the poster from the previous posted movie**<br>
Test types / techniques used: **Integration Testing**<br>
Response status code: **405 Method Not Allowed**<br>

![image](https://github.com/user-attachments/assets/165a7e26-c8f3-4040-9c66-8318be52b0ae)

<br>

JavaScript Tests:

![image](https://github.com/user-attachments/assets/7bd5bd76-a5c9-42ff-8f0f-503d1d887d3b)



<br>
</ol>

<h2>Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

![image](https://github.com/user-attachments/assets/0f838d66-e93a-4a3d-8583-cbdd1160478d)
![image](https://github.com/user-attachments/assets/7cf51d41-80b2-46b1-90af-8af547b19bd9)
![image](https://github.com/user-attachments/assets/37c89363-1000-4622-b03d-4ab8ad6387a4)
![image](https://github.com/user-attachments/assets/be9106c8-cc15-46a1-9a52-82c7e254e2e5)
![image](https://github.com/user-attachments/assets/da5ed91a-27f8-47e2-8907-34689ac164d4)

<br>

The collection was also run through newman directly from the terminal, and the results can be found below:<br>

![image](https://github.com/user-attachments/assets/36737b46-51bc-4b92-9920-7157076df417)


<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>

Bug: Posting a nonexistent movie title returns a wrong response<br>
Preconditions: Use a random, non-existent movie title.<br>

Steps to reproduce:<br>
1.Send a POST request to request to''http://www.omdbapi.com/t=FakeMovie&apikey=VALID_KEY'.<br>
2.Observe the response.<br>
Expected result: API should return an appropriate error such as 'Movie not found'.<br>
Actual result: API returns an response with "Movie not found", but the  status code is 200 OK, instead of 401.<br>

Bug: Another bug or deficiency in the design of the OMDb API is that all fields, including imdbRating, are returned as strings instead of their appropriate data types, meaning that imdbRating should be a number instead of a string.<br>

Steps to reproduce:<br>
1.Send a request to http://www.omdbapi.com/?apikey=d0236222&t=Titanic.<br>
2.Observe the response.<br>
Expected result: The imdbRating field should be returned as a number.<br>
Actual result:  The field is returned as a string, requiring additional conversions to be used as a numeric data type.<br>


<h2>Conclusions</h2>

Conclusions on OMDb API Testing in Postman<br>
Testing Summary<br>
Total number of tests created: 11<br>
Total number of tests executed: 11<br>
Requirement coverage: Approximately 90% of the initial requirements were covered, including API response validation, error handling, and performance testing.<br>

Identified Risks<br>
Following the testing, the following risks were identified:<br>

Returning a 200 OK status code for a nonexistent resource can prevent proper error detection.<br>

End users may receive confusing or incorrect messages, as the application cannot distinguish between a valid response and an error.<br>

Returning all fields as strings, including numeric ones, may cause confusion and errors in data processing.<br>

Recommendations for improving the API:<br>

Error messages in the response body should be clear and accurately reflect the nature of the problem, helping developers and users understand the cause of the error.<br>

Return the correct status codes.<br>

Use appropriate data types, making it easier for developers to use and process the data.<br>


Lessons Learned<br>
Error messages should be clear and consistent to improve user experience.
