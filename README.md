# SW Secure Deploy

Security configs and deployment tips for a secure Shopware 6 setup.

## Links

- [Shopware 6 Security](https://docs.shopware.com/en/shopware-6-en/tutorials-and-faq/security-measures)
- [Shopware 6 Security Plugin](https://store.shopware.com/en/swag136939272659f/shopware-6-security-plugin.html)
- [Two Factor Authentication](https://github.com/runelaenen/shopware6-two-factor-auth)
- [FroshTools](https://github.com/FriendsOfShopware/FroshTools)
- [Update Shopware](https://www.thomaspeissl.com/blog/posts/2024-04-29-update-shopware-6-with-composer-update-no-scripts/)

## Usage

All codes should be inserted right at the beginning of the files.

- Add code from [.htaccess](.htaccess) to your `.htaccess` file.  
- Add code from [robots.txt](robots.txt) to your `robots.txt` file.

## Recommendations

- Install/Update the Shopware Security Plugin
- Update Shopware and apps/themes
- Enable Two Factor Authentication
- Verify production mode is enabled
- Verify backups are working
- Verify Shop Status (FroshTools)

## Advanced

- Use a creative admin user name
- Setup stricter rate limits (shopware.yml)
- Install extensions as composer packages
