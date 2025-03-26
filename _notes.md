# CMS Development Notes

## Setup

- Created a CMS developer sandbox account.
- Installed the HubSpot CLI
  - `npm install -g @hubspot/cli@latest`
- Ran `hs init` and selected my "CMS Developer Sandbox Account"
- Created a theme
  - `hs create website-theme my-website-theme`
- Uploaded the theme to a "my-website-theme" folder in your HubSpot account.
  - `hs upload my-website-theme my-website-theme`
- Viewed the files in the design manager of your HubSpot account (`Content` > `Design Manager`).
  - The design manager is an in-app code editor that displays the developer file system.
- Created a website page using the theme "CMS theme boilerplate" (to experience how content creators will use your templates and modules).

## Development

- `hs watch my-website-theme my-website-theme`
  - This command watches for changes to the theme and automatically uploads them to your HubSpot account.

## Resources

- [CMS Development Quick Start](https://developers.hubspot.com/docs/guides/cms/quickstart)
