# fsnextjsfb
# Full Stack Nextjs Firebase with PartCombinators
Code summary to facilitate the development of applications using NextJS and Firebase

1- base.
- fsnextjsfb_base - https://github.com/partcombinator/fsnextjsfb_base (Docker)

2- Login and Register
- html - https://github.com/partcombinator/fsnextjsfb_login_html (context, formik, yup, react-toastify)
- bootstrap - https://github.com/partcombinator/fsnextjsfb_login_bootstrap ( Bootstrap )
- taildwind
- styled-components

3- Login, Register and Crud.

4- Forms and Validations

5- Payments

6- Redux

7- Dockers

8- Firebase Rulers
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
