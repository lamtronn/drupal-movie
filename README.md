# FFW: Drupal Training

This is a template project for the Drupal training program in FFW. It enables you to run a Drupal development
environment on GitHub CodeSpaces.

## Prerequisites
- A [GitHub](https://github.com/) Account
- An uderstanding of [GitHub Codespaces](https://github.com/features/codespaces)

## Development environment setup

* Fork the repository in your personal GitHub account
* Open the project in CodeSpaces
* Open the terminale3e
* Set up the website by executing the followin script: `sh setup.sh`
* Run the development server: `./vendor/bin/drush serve`
* Open the "ports" tab (right next to the terminal) and use the link under the "Local Address" to open your drupal instance
* Admin credentials:
  * username: admin
  * password: 123

 ## Site structure
   The website includes:
   - Homepage
   - New movies
     - Movies details
   - Genres
     - Genre details
   - Actors
     - Actor details
   - Reviews
     - Review details
   - Contact us
   - Search results

## Requirements
  - [x] **Homepage Utilizing Drupal Paragraphs:**	<br />
      Craft a dynamic homepage with flexible content sections for featured reviews, genres, and new movies using Drupal Paragraphs and Views.
  - [x] Advanced Views with Exposed Filtering: <br />
      Create Views for movies, genres, and actors, incorporating relationships and exposed filters.
  - [x] Custom Content Types and Varied Field Types: <br />
      Develop distinct content types for movies and actors with all field types/widgets including text, list, date, entity reference, image (with image style) etc...
  - [x] Dynamic Content Display Using Blocks: <br />
      Implement strategically placed custom blocks for improved user interaction.
  - [x] Comprehensive Genre Taxonomy: <br />
      Build a detailed genre classification with dedicated pages for each genre.
  - [x] Commenting System: <br />
      Enable comments for user engagement.
  - [x] Search Features and Navigation: <br />
      Include advanced search functionality and intuitive navigation.
  - [x] Site Branding and Compliance Features: <br />
      Implement a custom site logo, site information, and a cookie consent pop-up.
  - [x] Editor Role Configuration: <br />
      Create an Editor role with specific content creation and editing permissions but without publishing rights and access to the site configuration.
  - [x] Integration of Webforms: <br />
      Add webforms for user submissions and customize them to align with the website’s theme.
  - [x] Monitoring 'Recent Log Messages': <br />
      Regularly check the 'Recent log messages' under the Reports section for any errors or issues. Document any anomalies and outline how they were addressed or how they could potentially be resolved.

## Installed modules
  - COOKiES: User consent management tool using library cookiesJSR.
  - Publish Content: Adds a 'Publish' or 'Unpublish' link on the node edit/view pages, and a 'Publish Link' field if the Views module is enabled.
  - Better Exposed Filters: Provides advanced options (e.g. links, checkboxes, or other widgets) to exposed Views elements.
  - Webform: Enables the creation of webforms and questionnaires.
...
# drupal-movie
