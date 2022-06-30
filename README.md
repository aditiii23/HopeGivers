# HopeGivers - The Best Smile you can Gift 🎁

## 💡Inspiration

- According to the statistics, nearly 4.8 million deaths are caused due to extreme cold. Many people don't even have proper warm clothes to protect them from the frostbiting cold.

- 🧣 On the other hand, we generally look for new styles and fashionable sweaters, jackets even boots every year. And in turn, discard the old clothes which can be used by the needy.

- 🌱 Nowadays, we don't find pure woollen garments easily. Instead, they are mixed with synthetic fibres. On throwing it away, the entire thing will take forever to biodegrade. Hence, just throwing away the garments is harmful to nature as well.

- Not even clothes, one can donate his toys and books as well from this website. This could be extremely joyous for small children and to the ones as well who want to study and accomplish much more in their lives!

---

## ⚙️ What it does?

HopeGivers is a web platform where you can upload and donate your used and discarded winter wears for the underprivileged. Either you will be contacted by Donation Centres or somebody in need of the items.

### Features:

- ⬆️ **Upload**: It provides a platform, where people can upload their discarded winter wear for the needy person or the donation centres around them to get contacted.

![LaunchPage](https://user-images.githubusercontent.com/56069235/176602073-074689ba-8b8b-43aa-8ec1-b26ae278f4af.png)

- 🔍 **Explore**: A unique 3D Globe UI displaying items to be donated for people to determine location easily and request.

![results_globe](https://user-images.githubusercontent.com/56069235/176602038-a8eac243-485e-4697-bb19-e07d54387304.png)

![request](https://user-images.githubusercontent.com/56069235/176602185-40ea8b60-f784-4e73-931a-d4040cc7b8d5.png)

- 💙 **Donation Centers**: If someone doesn't wish to donate individually, they can contact other donation organizations. A single page displaying contact details of a few popular donation centres.
![donation_centres](https://user-images.githubusercontent.com/56069235/176602124-e5c8400e-acd7-4cab-8a77-641a529f0e2e.png)

### Architecture:

The website is enabled to perform complete transaction cycle for a user such as **Register, Email Verification, Add/Delete Items and Logout**. There are also routes protected by both backend and frontend, to minimize unauthorized access (Access with invalid email, no login, wrong password). I have used JWT Tokens for Authentication.

---

## How we built it

<p align="left"> <a href="https://expressjs.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg" alt="express" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/html-5.png"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://img.icons8.com/color/48/000000/javascript.png"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" alt="mongodb" width="50" height="50"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://img.icons8.com/color/48/000000/nodejs.png"/> </a> <a href="https://postman.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1280px-React-icon.svg.png" alt="React" width="60" height="40"/> </a></p>
<br>

- **Frontend:** Reactjs, Javascript, HTML, CSS
- **Backend:** Nodejs, Expressjs
- **Databse:** MongoDB
- **Deployment:** Heroku
- **Tools:** Git

---

## Challenges I ran into 🙁

❗️Enabling image upload: Initially, I was uploading the image in the website directory only. Therefore, the project got too large in size. Also, it was not a scalable solution. Then after hours of scanning the Internet, I found the correct way to use _Cloudinary_. And then instead of saving the blob, I saved the link in the schema.

❗️Deployment configurations for Heroku: The Website crashed multiple times on deployment. Then I realized the problem was that I was not configuring the environment variables correct. Also, I was hard coding the PORT value which resulted in errors.

---

## Accomplishments that I'm proud of 😇

Implementing the Globe UI. Since I am most comfortable in Backend Development, I always had in mind to come out of my comfort zone. This time I tried to implement a decent UI along with a twist to the conventional 2D UI. So, I'm pretty happy that my project's design has come out to be better than I had expected.

---

## What I learned 🤔

- **Globe.js**: This is an amazing Library. Getting hold of a new library in 48 hours was a tough task. Especially when it is a major portion of the project. Still, I managed to learn some of the implementations.
- **Cloudinary**: I had never used the API to store and retrieve images before. So this was also new learning for me.
- **JWT Tokens**: All my previous projects were session authentication based. So, this time I switched to a more secure method of Authentication, JWT.

---

## What's next for HopeGivers- The Best Smile you can Gift :)

A lot of things can be done with this project.

- Idea wise, we can get in touch with the donation centres and have a tie-up with them. And send a small token for every person who contributes.
- We can also integrate Google Maps API so that during a road trip, people can stop in a way to donate the clothes.
- Technically, the UI needs to be more responsive.

---
