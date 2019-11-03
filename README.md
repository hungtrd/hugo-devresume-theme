# Hugo DevResume Theme

This is a Hugo port of [DevResume](//github.com/xriley/DevResume-Theme) - great looking resume/CV template 
designed for developers by Xiaoying Riley.






## Screenshot

![DevResume screenshot](https://raw.githubusercontent.com/cowboysmall-tools/hugo-dev-resume-theme/master/images/screenshot.png)






## Features

### Original

- Fully Responsive
- HTML5 + CSS3
- Built on Bootstrap 4
- 1000+ FontAwesome icons
- SCSS source files included
- Compatible with all modern browsers

### Added

- Google Analytics






## Demo

You can see it in action on [Hugo Themes site](http://themes.gohugo.io/theme/hugo-dev-resume-theme/).






## Contents

- [Installation](#installation)
- [Getting started](#getting-started)
    - [Copying files](#copying-files)
    - [Configuring](#configuring)
    - [Test your site](#test-your-site)
    - [Build your site](#build-your-site)
- [Contributing](#contributing)
- [License](#license)







## Installation

Within the root of your Hugo project execute the following:

    $ cd themes
    $ git clone https://github.com/cowboysmall-tools/hugo-dev-resume-theme.git









## Getting started

After successful installation as a minimum you need to take the following steps:

### Setup

Go to [`exampleSite`](//github.com/cowboysmall-tools/hugo-dev-resume-theme/tree/master/exampleSite) and copy 
[`config.toml`](//github.com/cowboysmall-tools/hugo-dev-resume-theme/blob/master/exampleSite/config.toml) 
to the root of your site. Open `config.toml` and add your relevant information.

### Viewing

To view your site, execute the following: 

    $ hugo server -D

and go to `localhost:1313` in your browser.

### Building

Run:

    $ hugo

to generate your site in the `public` folder within the root of your project.







## Contributing

Post bugs and contributions to the [issue tracker](//github.com/cowboysmall-tools/hugo-dev-resume-theme/issues). 
Or make a [pull request](//github.com/cowboysmall-tools/hugo-dev-resume-theme/pulls).







## License

This template is 100% FREE as long as you keep the footer attribution link. You do not have the rights to resell, 
sublicense or redistribute (even for free) the template on its own or as a separate attachment from any of your work.
If you’d like to use this template without the footer attribution link, you can buy the 
[commercial license](https://themes.3rdwavemedia.com/bootstrap-templates/resume/devresume-free-bootstrap-4-resume-cv-template-for-developers/)

You may change the "Ported for..." line by adding the following to the end of `config.toml`
    
    [params.footer]
        copyright = ""

