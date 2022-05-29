# MoviesSearcher
Application was made to search movie entries from the database using Razor Pages, EntityFrameworkCore and ASP.NET MVC Core.
<br>
Application is the result of Microsoft's tutorial about creating <a href="https://docs.microsoft.com/en-us/aspnet/core/tutorials/razor-pages/?view=aspnetcore-6.0">web app</a>.
<br>
<br>
<b>The application meets the assumptions of SOLID, DI and DRY</b>.
<hr>

## How does it work

  Application creates a movie database for a company and stores the instances for passing them to the application user.
  
  Website redirect the user on start to the home page containing header and a link to my Github profile.
<p align="center">
  <img src=https://user-images.githubusercontent.com/74014874/170881652-52bf4698-f9dd-4eba-983d-472cb72a51b4.png
   >
</p> 
  There are some redirects on the top to allow the user change current page scene.
  After entering <b>Movies</b> API allows you to maintain certain operation through a website.
  <br>
  Allows the user to <b>get, put, post</b> and <b>delete</b> data.

<p align="center">
  <br>
  <img src=https://user-images.githubusercontent.com/74014874/170881802-959e7e0c-7e70-4c1e-948a-cbddb4c65c64.png
   >
</p>
<p align="center">
  <img src=https://user-images.githubusercontent.com/74014874/170882044-613c7aaa-499f-43c6-8afc-cba0521b1157.png
   >
</p>

  There is also an option to filter by movies by a category or the title.

<hr>
<p>
<b>API is connected to my database by default and to set up yours you need to change ConnectionString in the file appsettings.json</b>
</p>
