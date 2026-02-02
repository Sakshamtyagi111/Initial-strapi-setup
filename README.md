
Hey team! I've completed the first phase of the DevOps assessment. I hit a few roadblocks early on with the initial repository clone, but I managed to get a clean Strapi instance running locally and configured.

How I set this up
Installation: I started by trying to clone the main Strapi repo, but I realized it was a monorepo and didn't have the develop script I needed. To fix this, I used npx create-strapi@latest my-project --quickstart to get a fresh, working environment.

Content Building: I set up a collection type called Product with two fields: title and price.

Testing the CMS: I added a sample entry for a keyboard with a price of 2,500 (as seen in my screenshot) to make sure the data persistence and admin panel were working correctly.

GitHub Push: Once everything was verified locally, I initialized git, added a .gitignore, and pushed the source code to my repository.

Project Structure
src/api/product: This is where the schema for the keyboard entry lives.

package.json: Contains the scripts I used to run the dev environment.

Links
Loom Video: [https://www.loom.com/share/94262eb60c6f41dda1e8684132f68902]

[]
