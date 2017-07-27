## CMS concepts

### Traditional CMS

*Provide an end-to-end solution from editing content to displaying content via a theme system.*

**Pros:**
- Quick to build site using various available themes.
- Off-the-shelf support for previewing content **while** editing.
- High performance in content delivery.

**Cons:**
- *Front-end* implementation is bound to limitations of the theme system.
- Impossible to separate *back-end* and *front-end* concerns (e.g programming language, hosting...) due to its coupled nature.
- Tricky to add additional security layers on just *back-end* only.


### Headless CMS

*Focus only on content editing, with content APIs for custom front-end implementation.*

**Pros:**
- Freedom to pick the **right** technology for *front-end* part of the site.
- Having a single source of truth (data) makes it easy to distribute contents via multiple channels, e.g mobile app, affiliate sites...
- Easy to add additional security layers to *back-end* without any compromises to *front-end*.

**Cons:**
- Require additional work for content previewing.
- Ensuring fast and efficient content delivery can be tricky.
- Sharing authentication session between *back-end* and *front-end* is challenging.


## CMS platforms

### Content as a Service (CaaS)

*On demand content delivering service, e.g [prismic.io](http://prismic.io),  [contentful](https://www.contentful.com/)*

**Pros:**
- Zero hassle on maintenance.
- Minimal *back-end* work required.

**Cons:**
- Design is bound to limitations of the service capabilities.
- Potentially high on-going cost.


### Self-hosted CMS

*Hosting yourself CMS system, e.g [Wordpress](https://wordpress.org/), [Craft](https://craftcms.com/)*

**Pros:**
- Freedom to fully customise content models to fit with design.
- No on-going cost (hosting cost still applied however).
- Can be configured to be either traditional or headless CMS.

**Cons:**
- Required frequent maintenances to stay well performed and secured.

## CMS options

|  | prismic.io | Contentful | Wordpress | Craft |
| --- | --- | --- | --- | --- |
| **Functionality** |  | good |  |  |
| **Usability** |  | good |  |  |
| **Extensibility** |  | bad |  |  |
| **Deployability** |  | ?? |  |  |
| **Support** |  | ok - great |  |  |

### [prismic.io](https://prismic.io/)

*One CMS Backend for all your Websites & Apps.*

**Functionality**

**Usability**

**Extensibility**

**Deployability**

**Support**

### [Contentful](https://www.contentful.com/)

*Contentful is the essential content management infrastructure for projects of any size, with its flexible APIs and global CDN.*

**Functionality**
- Flexible content modelling.
- CDN'ed without having to set up CDNing an api.
- Built in localisation.
- Built in Rest API.
- Schema source control.
- Robust image editing tools.
- No repeater or flexible content field type.
- No hierarchal content types (can probably fake it using relationships, but won't display that way in the cms)

**Usability**
- How content and content models are mixed together in the same interface can be confusing.
- Editing content is fairly simple, and editing content models is also pretty simple.

**Extensibility**
- Can only use provided integrations and there are not many.

**Deployability**
- It is possible to import / export content and structure. I can't figure out from the docs whether its possible to just export structure and import it into another space without over-riding everything in the target space.

**Support**
- Depending on plan you can get varying quality of support, from basic ticketing to a dedicated contact and phone support.


### [Wordpress](https://wordpress.org/)

*WordPress is open source software you can use to create a beautiful website, blog, or app.*

**Functionality**

**Usability**

**Extensibility**

**Deployability**

**Support**

### [Craft](https://craftcms.com/)

*Craft is a content-first CMS that aims to make life enjoyable for developers and content managers alike.*

**Functionality**

**Usability**

**Extensibility**

**Deployability**

**Support**
