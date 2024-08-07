# Dave - The simple things make a big difference

## About Me
I'm Dave, a passionate web developer with a wealth of experience in various technologies and a talent for crafting innovative solutions. I've finally made a GitHub repository to showcase all of my pet projects and tools that I have built over the years. While many of these projects are primarily in PHP/HTML/JS/CSS, I am looking to expand my expertise by exploring other languages and frameworks-so watch this space!

## Projects

### Project 1: Telegram Bot
- **Description**: I developed a Telegram bot using Node.js that leverages the Telegram HTTP API. This project stemmed from my participation in several Telegram groups, where I noticed the need for a more effective bot to manage group activities and combat spam. After researching existing bots and their limitations, I created a solution that sets custom rules for better spam filtering and user interaction.
- **Key Features**:
  - **Advanced Spam Filtering**: Maps Cyrillic characters to their Latin equivalents and removes spaces to thwart common spam tactics.
  - **Content Control**: Restricts the sharing of YouTube links to those that offer value to the group.
  - **Custom Admin Permissions**: Allows designated users (not necessarily admins) to mute or ban members, providing more flexible group management.
  - **Custom Commands**: Features adaptable rulesets and custom Telegram commands to enhance group functionality.
  - **Multi-Chat Support**: Manages multiple chats with distinct bots, each configured with its own set of rules.
  - **Word Banning**: Automatically deletes messages containing specific words and determines appropriate actions, such as banning users who frequently cause disruption, particularly through attachments.
- **Technologies Used**: Node.js, Express, Telegram HTTP API
- **Repository Link**: [GitHub Repository](https://github.com/davey1992/Telegram-Bot)

  ___

### Project 2: Image Optimiser
- **Description**: With Google Page Insights scores in mind, I developed a PHP/jQuery Ajax tool to optimise JPG/PNG images and create WebP versions (a second-generation format). The tool adjusts image quality and generates WebP files using the PHP GD Library. It also includes custom HTACCESS rules to ensure browser compatibility and file existence, providing both JPG and WebP formats. The tool efficiently processes large volumes of images to prevent server timeouts.
- **Key Features**:
  - Image Optimization: Converts images to a specific quality and creates WebP versions.
  - Bulk Processing: Handles over 10,000 images across multiple directories, ensuring efficient processing without server timeouts.
  - PHP/jQuery Ajax Tool: Utilizes PHP GD Library and jQuery Ajax for seamless image processing.
  - Creates images in a new desired folder respecting the folder path
  - Fixes mime types issues with JPG/JPEG and PNG
- **Technologies Used**: PHP, jQuery, Ajax, PHP / PHP GD Library, HTACCESS
- **TODO**:
  -  To review file path extensions as it doesn't respect existing .JPG or .jpg which on linux systems will create two files.
  -  To strip out unndeeded files in this project, was going to be included into a custom CMS (discontinued)
  -  To do a direct replacement of images
  -  I fully intend to create a new repo of this and add support for a Wordpress Plugin with some options.
- **Repository Link**: [GitHub Repository](https://github.com/davey1992/Image-Optimiser)
