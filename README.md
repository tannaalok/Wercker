![Continuous-Integration](/../screenshots/public/pe_ci.jpg?raw=true "Continuous-Integration")
# Continuous Integration
---
[![wercker status](https://app.wercker.com/status/e87f2a2132e6558d836e3e3a6a212b68/s/master "wercker status")](https://app.wercker.com/project/byKey/e87f2a2132e6558d836e3e3a6a212b68)

This is an example of using Wercker for continuous integration from the Product Engineering blog.

Check out the post [here](https://medium.com/product-engineering/continuous-integration-with-wercker-e5d23b65cf7b#.9w385g2xo).

### Development
* `npm run start`

### Tests
* `npm run test`

### Deployment
* Pushes to master branch will trigger Wercker CI.
* Manual build of the app with `npm run build`
