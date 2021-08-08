# vulongtran.github.io
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/vulongtran/vulongtran.github.io">
    <img src="https://pages.vulongtran.com/images/dejavu-logo.png" alt="DejaVu">
  </a>

  <h3 align="center">DejaVu</h3>

  <p align="center">
    This project is built to demonstrate how to create a simple website with a login section.
    <br />
    <a href="https://github.com/vulongtran/vulongtran.github.io"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://pages.vulongtran.com/">View Demo Website</a>
    ·
    <a href="https://github.com/vulongtran/vulongtran.github.io/issues">Report Bug</a>
    ·
    <a href="https://github.com/vulongtran/vulongtran.github.io/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project is built to demonstrate how to create a simple website with a login section.
[![DejaVu demo website here]](https://pages.vulongtran.com)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  # Run this command in your project root folder.
  npm install @okta/okta-signin-widget@5.9.2
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/vulongtran/vulongtran.github.io.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```


#### Okta CDN

This demo website will use Okta's login assets directly from Okta's CDN. We are using this as:
1. It's the fastest easy way to get started with the widget, and/or
2. Want to keep things simple
3. We do not have an existing build website design that is already leveraging external dependencies such as [npm](https://www.npmjs.com/).

To embed the Sign-in Widget using Okta's CDN, we will include the following JS and CSS files in our website HTML:

```html
<!-- Latest CDN production Javascript and CSS -->
<script src="https://global.oktacdn.com/okta-signin-widget/5.9.1/js/okta-sign-in.min.js" type="text/javascript"></script>

<link href="https://global.oktacdn.com/okta-signin-widget/5.9.1/css/okta-sign-in.min.css" type="text/css" rel="stylesheet"/>
```

Please do note that the CDN URLs contain a version number. This number should be the same for both the Javascript and the CSS file and match a version on the Okta's [releases page](https://github.com/okta/okta-signin-widget/releases).

Test Release link [releases page](/releases).


<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/vulongtran/vulongtran.github.io/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/coolfeature`)
3. Commit your Changes (`git commit -m 'Add some cool feature'`)
4. Push to the Branch (`git push origin feature/cool feature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the Apache License. See `LICENSE` for more information.


<!-- CONTACT -->
## Contact

Vu Long Tran - [@vulongtran](https://twitter.com/vulongtran)

Project Link: [https://github.com/vulongtran/vulongtran.github.io](https://github.com/vulongtran/vulongtran.github.io)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements/ References
* Website hosting[Github Pages](https://pages.github.com/)
* Website template - [Pavo Template by Inovatik](https://onepagelove.com/pavo)
* Login plugin widget used [Okta Sign-In Widget Guide](https://developer.okta.com/code/javascript/okta_sign-in_widget/)
* Okta Sign-In Widget Github page [Okta Sign-In Widget](https://github.com/okta/okta-signin-widget#using-the-okta-cdn)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://linkedin.com/in/vulongtran
