# Jazz Townsville

## Installation & Setup

* Install [XAMPP](https://www.apachefriends.org/)
* Download and install [Wordpress](https://www.wordpress.org/)


* Clone this repo into wp-content > themes<br>
`git clone https://github.com/cp3402-students/2020-sp1-project-cp3402-2020-team26.git`
* Tools > Import > WordPress > Run Importer > Upload > `jazztownsville.WordPress.2020-05-20.xml`


* Apperance > Home page settings > A static page > Home page > `Home`
* Apperance > Home page settings > A static page > Posts page > `-Select-`
* Apperance > Customize > Site Identity > Site Title > `Jazz Townsville`
* Apperance > Customize > Site Identity > Tagline > `Townsville Jazz Club`
* Apperance > Customize > Site Identity > Display Site Title and Tagline > `Uncheck`
* Apperance > Customize > Widgets > Sidebar > `remove all widgets`

## Adding Content
* To add content to the site, you simply edit each page using the block formatting 
* For future updates (such as newletters and announcments) is done through the posts aspect of 
* Wordpress, these new updates and announcements will be posted to the homepage.

## Plugins
* Membership Form - the membership form is created and updated using the [WPForms](https://wpforms.com/) plugin, this allows for easy use
* Audio - All audio is done through the [HTML5 Player](https://wordpress.org/plugins/html5-audio-player/) plugin
* Photos - Photo galleries uses the LightBox with [Photoswipe](https://wordpress.org/plugins/lightbox-photoswipe/) plugin, makes it easier to update and add photos to galleries

## Management
* [WP pusher](https://wppusher.com/) is a plugin used for requesting updates from the Github repository, making the developtment easier for transition from 
* local to Staging server
* Content Backup is done using a backup plugin called All-in-one WP migration (https://en-au.wordpress.org/plugins/all-in-one-wp-migration/)
* To do this you simply create a backup and save it as an archive, then on the production server you import that archive, this brings everything except theme.
