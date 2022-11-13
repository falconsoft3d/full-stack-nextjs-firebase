# fsnextjsfb
# Full Stack Nextjs Firebase with PartCombinators
Code summary to facilitate the development of applications using NextJS and Firebase

1- base.
- fsnextjsfb_base - https://github.com/partcombinator/fsnextjsfb_base (Docker)

2- Login.
- html
- bootstrap
- taildwind
- styled-components

3- Login and Register.

4- Login, Register and Crud.

5- Forms and Validations

7- Payments

8- Redux

9- Dockers

10- Firebase Rulers
```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
       allow read, write: if request.auth != null;
    }
  }
}
```

# My Contact Info
Marlon Falcón Hernández | Valencia | Spain
```
* ERP, CRM y Software: https://www.marlonfalcon.com
» Email: mfalconsoft@gmail.com , falconsof.3d@gmail.com
» Github: https://github.com/falconsoft3d
» linkedin: https://linkedin.com/in/marlon-falcón-3a2aa9a4
```
