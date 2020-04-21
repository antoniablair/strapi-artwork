# strapi-artwork
Strapi CMS app for managing digital artwork and slideshows

Run yarn install and yarn develop / yarn start to kick off the application. By default strapi will use sqlite3, however
you can set up MYSQL or PostgreSQL for production. 

If running in development mode, visit localhost:1337/admin and you will be prompted to create an initial administrator user. 
You should now be able to login to an admin panel at localhost:1337/admin .

## API
API endpoints can be viewed at `{yourdomain}/slideshows` and `{yourdomain}/artworks`, however you will either need
to make the API endpoints public or create a user with permission to access them. 

For example, for public fetching, go into Roles & Permissions from left-side blue menu. Select Public and select "find" and "findOne" on both Artworks and Slideshows. Click save. 

## Adding artworks or slideshows
You can then upload artwork by going to the left-side menu and selecting "Artworks". 

To add the artworks to a slideshow, create a slideshow. On the right side of the Slideshow editor, you will see
a dropdown called "Artworks", which you can use to search for your artwork by name.
