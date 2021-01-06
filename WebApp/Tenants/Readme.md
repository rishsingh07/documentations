# Tenants
**Description:** A tenant is a partner of *Plant for the planet* which will host our web application on their domain and take care of the marketing of the same.
for example: (https://trees.salesforce.com/) 

> 1. How to become a tenant?
 Please contact partner@plant-for-the-planet.org 


***Features provided to our Tenants.***

- [x] *Custom Domain* - Tenant will be provided with a customised domain as per their requirements.

- [ ] *Custom Leaderboard Page* - A customised leaderboard is where one can view the number of trees planted by them as well as by other peers. (if necessary, please add link to designs)

- [ ] *Multiple Language* - A tenant can view their project as per their own regional language i.e: Germany, Spanish, English, Portuguese. (please list languages)

- [ ] Tenant Description on the Leaderboard Page (If default template) and the tree target

- [ ] If hosting at subdirectory, current server type (NGINX/APACHE)

- [ ] Enable Authentication (Read more)

### Customisations Available



### Steps for Authentication: 
We use Auth0 to integrate authentication and authorization in a web application.
1. Signup on [Auth0](https://auth0.com/)
2. Get client ID (Auth0 SPA App)
3. Callback URLs : [tenantURL]/verify-email, [tenantURL]/login
4. Logout URLs: [tenantURL]/verify-email, [tenantURL]/

2. Requirements:
- Custom Domain (Required)
- Logo URL (Required)
- Custom fonts url: (woff, woff2) - (Optional)
- Mapbox token (Required)
- Generate Favicons at: https://iconifier.net
- Auth0 client ID (Optional)
- List of languages
- Short description
- Tree target





**Checklist for Developer**

- [ ] Tenant is present in the Backend
- [ ] Completed Meta.json file and any translations
- [ ] Completed tenant.config file
- [ ] Svg logo url:
- [ ] Custom fonts (woff, woff2) url:
- [ ] Generate new maxbox token
- [ ] Use ASSET_PREFIX with maxcdn if high traffic site
- [ ] Generate Favicons at: https://iconifier.net
