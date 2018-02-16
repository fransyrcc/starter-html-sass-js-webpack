# Site with Webpack Boilerplate

### Golden rule: Keep It Simple and Straightforward (KISS)

Keep it simple and straightforward but good enough so it can become a large site or application.

### Install dependencies

- Run `npm install`

### Development

- Run `npm run dev`
- In your browser, navigate to: [http://localhost:8080/](http://localhost:8080/)

### Resources

- [Generate your icons](https://www.favicon-generator.org/)
- [SVG optimizer](https://jakearchibald.github.io/svgomg/)

### Publish

1. In `webpack.config.js` file, replace `www.example.com` with the real domain name.

2. Run `npm run build`

3. Copy the following folders/files to web server

	- /dist
	- /images
	- index.html

## Discussions

### Rendering high resolution images
This repo uses retina.js to serve high-resolutions images to devices with retina display. It renders two images per image, one x1 and another x2, it means that the work is left for the browser. This method is not recomended for big sites.  Instead try to serve the right image from the server.

A good article about this is here:

[Retina & Hi-Resolution Displays: The ultimate guide to preparing your websit](https://mercury.one/wordpress/retina-hi-resolution-displays-the-ultimate-guide-to-preparing-your-website/)

### Responsive site and media queries usage

[The Difference Between Responsive and Adaptive Design](https://css-tricks.com/the-difference-between-responsive-and-adaptive-design/)

This repo uses media queries within the sass file. The sass way!

## How-to / Guidelines
- Webpack documentation: https://webpack.js.org/concepts/
- CSS guidelines: https://cssguidelin.es/#commenting
- SASS guidelines: https://sass-guidelin.es/
- Media queries: https://include-media.com/#documentation
- JavaScript guidelines (Google): https://google.github.io/styleguide/jsguide.html

# ToDo

Lots to do. But at least it is a start.
- http://sassdoc.com/
- templating index so each section is in its file