# Low impact principles for web
A list of things you can do to make your web a little greener. This is a work in progress and we will continue to add stuff in here. Feel free to help us out with submitting a PR for errors or new additions.


### Keep it short
Say only the neccesary things, and keep pages and content to a minimum. Be mindful of what you add to the internet – there's a lot of stuff there already.

### Minimal media. At least optimized media
Images, videos and so on are heavy on the bandwith. Try to think about alternative ways to convey the message. Also make sure that you are not sending large images or videos where it is not needed e.g mobile (this also helps performance). The service Cloudinary can be a lot of help in getting the correct formats and dimensions.

That said we think we will see a new movement with different types of compression e.g. pixelating content around the focus point of the image. Making the neccesary parts more visible than the other.

### Scalable Vector Graphics (SVG)
Svg has a very low impact. With all the possibilities using inline svgs with animation this should be a good tool to solve a lot of problems.

### SSG
Static generation takes all of your dynamic and static data and builds it one time per change/deploy. This will leave you with a static page in the end. No work on the server except sending the page.

### As little JS as necessary
Watch your bundle size, especially with heavier frameworks. Smaller bundle sizes = less network, less processing and better performance. Also keep an eye out for third party stuff like tracking, or other npm packages. A classic example is `moment` vs `date-fns`. Two packages that solves pretty much the same problem, but are quite different in bundle size. [Bundlephobia](https://bundlephobia.com/) can be at help for looking at npm packages.

### Dark mode 
Darker pixels require less light, which means less power to the monitor

### Hosting
Look for green alternatives, or host your own solar powered server like [LOW←TECH MAGAZINE](https://solar.lowtechmagazine.com/)

### Tooling
* [Import cost vscode plugin](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
* [Website carbon a carbon footprint calculator](https://www.websitecarbon.com/)
