<h3> Backend software developer with 10 years experience in network operations. Enthusiastic about complex logic, security and green tech.  Recent graduate of the Turing School of Software and Design focusing on Ruby, Rails and Object Oriented Programming.</h3>

<h4>
Software Engineering Grad: <a href='https://turing.edu'>Turing School of Software & Design</a><br>
Currently learning: Python<br>
Email: <a href='menyeart1@gmail.com'>menyeart1@gmail.com</a><br>
Connect with me: <a href='https://www.linkedin.com/in/matt-enyeart/'>LinkedIn</a>
</h4>

<h3 align="center">Technology Stack</h3>
<p align='center'>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192603745-7d34df9e-7756-4756-a539-6a61badf7a80.png' title="Ruby" alt="Ruby Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192603748-3ac17112-3653-4257-80da-a57334b11411.png' title="Rails" alt="Rails Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/117208740-bfb78400-adf5-11eb-97bb-09072b6bedfc.png' title="Postgres" alt="PostgreSQL logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/101955307/208489328-fd830258-94a9-4470-8ed8-2acbbb978f9b.svg' title="CSS" alt="CSS" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192603750-4142ae75-10fa-4b61-a773-8b2052834357.png' title="Ruby Gems" alt="Ruby Gems Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png' title="HTML" alt="HTML Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192107854-765620d7-f909-4953-a6da-36e1ef69eea6.png' title="HTTP" alt="HTTP Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png' title="Git" alt="Git Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png' title="Github" alt="Github Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/101955307/208492362-1f2a051d-9a16-4098-ab31-c44bf4d5aec7.svg' title="VSCode" alt="VSCode" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192109061-e138ca71-337c-4019-8d42-4792fdaa7128.png' title="Postman" alt="Postman Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/101955307/208492752-4ccd10ee-0a00-4b79-8576-b06a3c078697.svg' title="CircleCI" alt="CircleCI" height="50"/>  
<img align="center" src='https://user-images.githubusercontent.com/25181517/192107858-fe19f043-c502-4009-8c47-476fc89718ad.png' title="REST" alt="REST API Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/192107856-aa92c8b1-b615-47c3-9141-ed0d29a90239.png' title="GraphQL" alt="GraphQL Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png' title="Jupyter Notebook" alt="Jupyter Notebook Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png' title="JavaScript" alt="JavaScript Logo" height="50"/>
<img align="center" src='https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png' title="Python" alt="Python Logo" height="50"/>
</p>
<br>

<h2> Recent Personal Projects </h2>

<h3>Front Range Freeway Forecast</h3>
<h4>Overview:</h4>
<p>&nbsp&nbsp A small service oriented application using Google's Direction Matrix API to forecast the best travel times for users traversing Colorado's I70 during the winter ski season. </p>
<h4>Comments:</h4>
<p>&nbsp&nbspMost seasoned skiers know if you get on I70 during ski season before 6AM you'll probably have an OK time, whereas if you get on I70 after 6AM your trip duration might double. Front Range Freeway Forecast was meant to be a way of predicting future drive durations based on historical traffic data in combination with curerrent conditions. Users would then be able to optimize sleeping in vs sitting in traffic via an easy to understand dashboard of drive time predicitions for each resort. Unfortunately, while Google's traffic data is probably vast, there's not much confidence in the predicted drive times. Furthermore, the API's cost combined with its terms of service(no caching any drive time duration data) make delpoying this a possibly expensive proposition. The frontend controller also probably isn't quite RESTful, sending params to the controller without making another backend request was a hacky way of making the page feel dynamic without appending to the DOM or modifying the backend endpoints. </p>

<p>The landing page:</p>
<img width="1516" alt="Front Range Forecasat Landing Page" src="https://github.com/menyeart/menyeart/assets/92339276/65a67667-c21f-4018-8296-14ed9afbbbe3">
<p>Forecast Response from the backend:</p>
<img width="623" alt="Screenshot 2023-09-29 at 2 08 44 PM" src="https://github.com/menyeart/menyeart/assets/92339276/665250f8-e91a-45eb-b5ea-bb2cda03fc3e">


<h3>Site Squirrel</h3>
<h4>Overview:</h4>
<p>&nbsp&nbspOriginally designed to be a fully featured service oriented application utilizing Booze Allen Hamiltion's Recreation.gov API, Site Squirrel would let users would set up trips and then receive notifications when hard to find National Park campground reservations became available. Site squirrel was discontinued/transitioned to a backend API only application after recreation.gov recently implemented notifications features natively. </p>
<h4>Comments:</h4>
<p>&nbsp&nbspAfter several years of not having a notifactions feature, seeing BAH implement it natively in recreation.gov mid project was a little dissapointing. Personal projects are fun, but they're a lot more fun if they're actually used and I was excited to deploy this for my friends and colleagues. Futhermore, the recreation.gov API only allows arround 500 requests an hour whereas you may may need to make requests for many campgrounds every few minutes. Working to scale the application to allow a reasonable amount of users while still making enough requests per campground to be effective in getting a reservation seemed like a real challenge.  </p>

<p>A sample request and response:</p>
<img width="700" alt="Screenshot 2023-09-29 at 1 54 31 PM" src="https://github.com/menyeart/menyeart/assets/92339276/54fe96ff-e8fe-4be1-8629-f7713b9da99f">
<p>Database Tables:</p>
<img width="700" alt="Screenshot 2023-09-29 at 1 54 31 PM" src="https://github.com/menyeart/menyeart/assets/92339276/b82ff992-4f65-4d61-a8bb-49f938d89ae9">
