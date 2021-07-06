# ResBaz Sydney 2021 website

### About

ResBaz Sydney 2021 will be a multi stream online event 23-26 November 2021. The program will feature key stories (like keynotes, but with a narrative!), workshops, short talks, demonstrations and lots of opportunities to find out about next gen tech and tools for researchers. Our program has dedicated streams for Compute, Humanities and Social Science, and Survey/ Data Collection, as well as two streams for introductory programming skills, which are open to all, regardless of skill level or discipline. Lots of breaks, lots of opportunities to find your people across institutions and disciplines, and plenty of neat tricks and hacks to level up on your nerd skills.

This website is based on the [GDG Zeppelin conference website](https://github.com/gdg-x/zeppelin/) - credits at the end under Contributors

### Updates

For updates, raise an issue, and, if you can, a pull request with changes.

### Where things live

#### Information

The conference schedule is in _data/schedule.yml

Individual sessions are in _data/sessions.yml

Speaker bios are in _data/speakers.yml

#### Blog posts

Blog posts are Markdown files in the _posts section.

#### Pictures

Banners for the sections of the main page are in img/sections-background/

Banner images are 1200x490 px

Photos of speakers are in img/people/

Speaker photos are 400x400 px, and should have filenames which match the values in the thumbnailUrl slots in speakers.yml, for eg "JaneSmith.jpg" below

    - 
      id: 1
      name: "Jane"
      surname: "Smith"
      company: "University of Research"
      title: "Repository Manager"
      bio: "Sample bio"
      thumbnailUrl: JaneSmith.jpg
      rockstar: true
      social: 
        - {name: "twitter", link: "https://twitter.com/JaneSmith"}








### Contributors


* Design and web development: [Oleh Zasadnyy](https://github.com/ozasadnyy)
* Idea: [Vitaliy Zasadnyy](https://github.com/zasadnyy)

See [list of contributors](https://github.com/gdg-x/zepplin/graphs/contributors)

Maintainers: [@tasomaniac](https://github.com/tasomaniac) and [@ozasadnyy](https://github.com/ozasadnyy).

### License
Project is published under the [MIT license](https://github.com/gdg-x/zeppelin/blob/master/LICENSE.txt). Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)
