ng new ng01
ng serve
ng build
ng build --prod
ng test
ng e2e
ng help

1. Init Repo (VSCode)

2. Create Repo (GitHub REST API)
-> curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"ng01"}'

3. Remote Add Origin
-> git remote add origin https://github.com/kwokhung/ng01

4. Push Origin Master
-> git push -u origin master

npm install --save @capacitor/core @capacitor/cli
