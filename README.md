# Twitter/X Container

**Prevent Twitter, or X  from tracking your visits to other websites**

This Project is a fork of [Mozilla's Facebook Container](https://addons.mozilla.org/firefox/addon/facebook-container/) and [Vishwa's twitter container](https://github.com/v1shwa/contain-twitter) modified to work with both Twitter and X, domains, update to include more recent features taken from firefox's official branch and improved all-around. 
<!-- For installation & Usage instructions follow this [link](https://addons.mozilla.org/en-US/firefox/addon/twitter-container/) -->

*Note: This addon is not affliated to Mozilla in anyway*
**Note:** To learn more about Containers in general, see [Firefox Multi-Account Containers](https://support.mozilla.org/kb/containers).

## How does Twitter/X Container work?

The Add-on keeps Twitter/X in a separate container to prevent it from following your activity on other websites. When you first install the add-on, it signs you out of Twitter/X and deletes the cookies that Twitter/X uses to track you on other websites. 

Every time you visit Twitter/X, it will open in its own container, separate from other websites you visit.  You can login to Twitter/X within its container.  When browsing outside the container, Twitter/X won’t be able to easily collect your browsing data and connect it to your Twitter/X identity.

## How do I enable Twitter/X Container?
PENDING 
<!-- 
We’ve made it easy to take steps to protect your privacy so you can go on with your day.

1. [Install Twitter/X Container](https://addons.mozilla.org/firefox/addon/Twitter/X-container/). This will log you out of Twitter/X and delete the cookies it’s been using to track you.
2. Open Twitter/X and use it like you normally would.  Firefox will automatically switch to the Twitter/X Container tab for you.
3. If you click on a link to a page outside of Twitter/X or type in another website in the address bar, Firefox will load them outside of the Twitter/X Container -->

## How does this affect Twitter/X’s features?

Twitter/X Containers prevents Twitter/X from linking your activity on other websites to your Twitter/X identity. Therefore, the following will not work:

### 'X' buttons and embedded Twitter/X comments on other websites.

Because you are logged into Twitter/X only in the Container, “Like” buttons and embedded Twitter/X comments on other websites will not work.

### Logging in or creating accounts on other websites using Twitter/X

Websites that allow you to create an account or log in using Twitter/X will generally not work properly.

## Will this protect me from Twitter/X completely?

This add-on does not prevent Twitter/X from mishandling the data it already has or permitted others to obtain about you. Twitter/X still will have access to everything that you do while you are on Twitter/X.com or X.com or on the Twitter/X app, including your X posts, photo uploads, faves, and any data you share with Twitter/X connected apps, etc.  

Other ad networks may try to link your Twitter/X activities with your regular browsing. In addition to this add-on, there are other things you can do to maximize your protection, including changing your Twitter/X settings, using Private Browsing and Tracking Protection, blocking third-party cookies, and/or using [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/ ) extension to further limit tracking.

## How do I use Containers for other websites?

Good news! Containers aren’t just for Twitter/X. You can use Containers to prevent websites from linking your identities across the Web by installing [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/).

To learn more about how Multi-Account Containers work, see our support page at [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/).

## Development

1. `npm install`
2. `./node_modules/.bin/web-ext run -s src/`

### Testing
`npm run test`

or

`npm run lint`

for just the linter

### Building

1. `npm run build`
2. use the add-on zip file generated in the `web-ext-artifacts` folder


### Links

- [License](./LICENSE)
