# strapi-artwork
Strapi CMS app for managing digital artwork and slideshows

Run yarn install and yarn develop / yarn start to kick off the application. By default strapi will use sqlite3, however
you can set up MYSQL or PostgreSQL for production. 

If running in development mode, visit localhost:1337/admin and you will be prompted to create an initial administrator user. 
You should now be able to login to an admin panel at localhost:1337/admin .

Go into Roles & Permissions and select Public. This is where you can change which users have access to which API endpoints,
or make API endpoints public. 

For example, for public fetching, go to public and select "find" and "findOne" on both Artworks and Slideshows. Click save. 

You can then upload artwork by going to the left-side menu and selecting "Artworks". 

To add the artworks to a slideshow, create a slideshow. On the right side of the Slideshow editor, you will see
a dropdown called "Artworks", which you can use to search for your artwork by name.
