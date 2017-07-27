## Concepts

### Traditional CMS

> Provide an end-to-end solution from editing content to displaying content usually via a theme system.

**Pros:**
- Quick to build site using various available themes.
- Off-the-shelf support for previewing content while editing.
- High performance in content delivery.

**Cons:**
- *Front-end* implementation is bound to limitations of the theme system.
- Impossible to separate *back-end* and *front-end* concerns (e.g programming language, hosting...) due to its coupled nature.
- Tricky to add additional security layers to the *back-end* only.


### Headless CMS

> Focus only on content editing, providing rich APIs for custom front-end implementation.

**Pros:**
- Freedom to pick the right technology for *front-end* part of the site.
- Having a single source of truth (data) makes it easy to distribute contents to multiple channels, e.g mobile app, affiliate sites...
- Easy to add additional security layers to *back-end* without affecting the *front-end*.

**Cons:**
- Require additional work for content previewing.
- Ensuring fast and efficient content delivery can be tricky.
- Sharing authentication session between *back-end* and *front-end* is challenging.


## Solutions

### Content as a Service (CaaS)

> On demand content delivering service, e.g [prismic.io](http://prismic.io),  [contentful](https://www.contentful.com/)

**Pros:**
- Zero hassle on maintenance.
- Minimal *back-end* work required.

**Cons:**
- Design is bound to limitations of the service capabilities.
- Manage content structure change can be difficult.
- Potentially high on-going cost.

### Self-hosted

> Hosting yourself CMS system, e.g [Wordpress](https://wordpress.org/), [Craft](https://craftcms.com/)

**Pros:**
- Freedom to fully customise content models to fit with design.
- No on-going cost (hosting cost still applied however).
- Can be configured to be either traditional or headless CMS.

**Cons:**
- Required frequent maintenance to stay well performed and secured.

## Options

|  | prismic.io | Contenful | Wordpress |
| --- | --- | --- | --- |
| **Stability & security** | Great | Great | Good |
| **Content flexibility** | Excellent | Good | Excellent |
| **Features** | Great | Good | Good |
| **Ease of use** | Great | Great | Good |
| **Ease of development** | OK | Good | Great |
| **Support** | Good | Good | Great |

### [prismic.io](https://prismic.io/)

> One CMS Backend for all your Websites & Apps.

| Stability & security | Content flexibility | Features | Ease of use | Ease of development | Support |
| --- | --- | --- | --- | --- | --- |
| Great | Excellent | Great | Great | OK | Good |

**prismic.io** is packed with features, some of them are fairly unique like ability to schedule releases, A/B testing contents. Its dashboard UI is very well designed and intuitive. Content editing is a breeze. Extensive list of fields type and no restrictions on number of custom types make it's easier to create re-usable set of components to compose web pages.

**prismic.io** comes with a command line to bootstrap your project, first-class support for NodeJS, React and Angular. High learning curve when querying complex contents though, and modification of content models (structure) after first production released is very challenging however, the [proposed solution](https://intercom.help/prismicio/how-to-guides/handling-several-environments-dev-production-with-a-prismicio-repository) is finicky at best.

Priority support comes at a higher on-going cost.

### [Contentful](https://www.contentful.com/)

> Contentful is the essential content management infrastructure for projects of any size, with its flexible APIs and global CDN.

| Stability & security | Content flexibility | Features | Ease of use | Ease of development | Support |
| --- | --- | --- | --- | --- | --- |
| Great | Good | Good | Great | Good | Good |

**Contentful** is a mature platform with a well thought-out feature set, its [Images API](https://www.contentful.com/developers/docs/references/images-api/) is best in class. Number of field types is somewhat small compared to **prismic.io** and lacks of repeating fields render composing new pages out of content blocks impossible.

**Contentful** provide SDKs for a great range of programming languages. Documentations are well written and its RESTful API structure helps easing down the learning curve. Like all other CaaS services, managing content structure change after production in Contentful is a challenge, but their [proposed solution](https://www.contentful.com/developers/docs/concepts/multiple-environments/) is acceptable.

Support scales with on-going cost, ranging from basic ticketing to a dedicated contact and phone support.

### [Wordpress](https://wordpress.org/)

> WordPress is open source software you can use to create a beautiful website, blog, or app.*

| Stability & security | Content flexibility | Features | Ease of use | Ease of development | Support |
| --- | --- | --- | --- | --- | --- |
| Good | Excellent | Good | Good | Great | Great |

**Wordpress** is arguably one of the most popular CMSs out there, due to its maturity and tremendous amount of support from open source community. Its rich Plugins ecosystem helps building site much faster. Overusing plugins can be a major issue, however, as they are the main source of security risks and performance degradation. Configure Wordpress to a headless CMS will eliminate most of these issues.

**Wordpress** theme system feels outdated and lacks of modern PHP features. Several efforts ([here](http://framework.themosis.com/), [here](https://roots.io/bedrock/) and [here](https://github.com/gladeye/blueprint)) have been made to address this issue, make working with Wordpress a lot more enjoyable.

