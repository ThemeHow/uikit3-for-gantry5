# :page_facing_up: Custom UIKit Particles for Gantry
A (Gantry) Particle is a small block of data used on the front-end. It acts a lot like a widget/module, but can be easily configured with a GUI in the Gantry 5 Administrator.

This a small collection of self-created Gantry Particles for the different components available for UIKit.

**IMPORTANT:** For all particles the integration of the UIKit Front-End Framework is absolutely mandatory! This can be done e.g. by using the *UIKit Atom* (see below) in the Basic Outline of the Gantry Theme Framework.

**NOTE:** Only tested with [Joomla! CMS](https://www.joomla.org/) so far! But it should work for [Wordpress CMS](https://wordpress.com) and [Grav CMS](https://getgrav.org/) as well...

**Latest tested versions:** *(No backwards compatibility to UIKit v2 and Gantry 4!)*
 + Gantry: 5.4.22 
 + UIKit: v3.0.0-beta.40

## Included Particles & Atoms
### UIKit Atom (mandatory for using the UIKit Particles below!)
+ **UIKit Atom** (uikit-for-gantry)

   Includes all the necessary CSS and JS-files for UIKit.<br>
   Files: [`uikit-for-gantry.html.twig`](https://github.com/j0hu3ttl/uikit3-for-gantry5/blob/master/custom/particles/uikit-for-gantry.html.twig) and [`uikit-for-gantry.yaml`](https://github.com/j0hu3ttl/uikit3-for-gantry5/blob/master/custom/particles/uikit-for-gantry.yaml).

### Particles
*...more will be added...*

## How to use?
Using the particles on your website is a really easy! Just follow these steps:

**Installing on Joomla! CMS**
1. Download the particle you want (or multiple/all).
   
   Each particle consits of two files - `<PARTICLE_NAME>.html.twig` and `<PARTICLE_NAME>.yaml`.

1. Copy the files to `<JOOMLA_ROOT>/templates/<TEMPLATE_DIRECTORY>/custom/particles/` - maybe you will need to create it manually.

1. Have fun and use the particle(s)!

Basically, these steps are the same as in the [Gantry 5 Documentation](http://docs.gantry.org/gantry5/advanced/creating-a-new-particle).

## Links
**Gantry Theme Framework**
 + Website: http://gantry.org/
 + Documentation: http://docs.gantry.org/
 + GitHub: https://github.com/gantry/gantry5
 
**UIKit Front-End Framework**
 + Website: https://getuikit.com/
 + Documentation: https://getuikit.com/docs/
 + GitHub: https://github.com/uikit/uikit

## Contributing
1. Fork the repo.
1. Make any changes you want.
1. Make a pull request and wait for approval.

## License
All content is licensed under [MIT-License](https://github.com/j0hu3ttl/uikit3-for-gantry5/blob/master/LICENSE).
