IMPORTANT - as I went to upload my completed CSS I recieved an error message from GITPOD and I cant commit or push my completed CSS. The error message stated the following. 

hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
gitpod /workspace/sh-fish-chips $ git pull <remote> master:dev
bash: remote: No such file or directory
gitpod /workspace/sh-fish-chips $ git pull origin master 
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: couldn't find remote ref master
gitpod /workspace/sh-fish-chips $ git pull origin master //
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
   ![Screenshot 2021-10-30 at 22 31 52](https://user-images.githubusercontent.com/89813192/139572930-2a3e664c-5f44-4df2-9517-1fe853eeb3e3.png)

  
  
All of the work I completed was local so I am unable to pull files from anywhere. The project is due in on 31/10/21 at 12 Noon. I understand that I am going to initially fail this project but this issue is out of my control and completley outside of my capabilites (or the majority of people at this point in the course). to solve in the timeframe before I need to hand this project in (I have started off as a complete beginer). I feel that this issue has unfairly put me in a positon of failing so when possible I would like to discuss re-submissions. I can show and prove that I have completed the work within this read.me but it will not be applied to the finished website that will be seen.
  
  Underneath is the completed CSS.
  *{
    margin: 0;
    padding: 0;
    border: none;
}
.body {
    background-color:#003d7a;
    font-family: 'courgette' , cursive;
    background-color: #77b3eb;
 }
 #logo{
     letter-spacing:2px;
     color:#021a31
 }
 #menu a:hover{
     border-bottom: 2px #021a31;
 }
 @media screen and (max-width: 1200px){
     
 }
  #form-heading{
    padding: 20px;
    text-align:center;
 }
 #footer-color {
    background-color:#c8e4ff;

 }
 .form-group{
     padding:10px;
    
 }
 h1,h2,h3,h4,h5,h6,p{
    font-family: 'Courgette', cursive   
 }
.navbar {
    height: 200px;
    background-color: #8ec1d1;
    margin-bottom: 0;
    border-radius: 0;
}
.navbar, a {
 color:#00264d
 ;padding: 3px;
 margin: 0 
}
#background-color-contact-us{
    background-color:#021a31;
}
#contact-us-black-text{
    color:#021a31
}
.container-bg {
  background-color: #c8e4ff;
}
.container {
text-align: center;
}
 .sidenav {
background-color: #c8e4ff;
height: 100%;
 }
.row{
text-align:center 
 }
.ish-position {
    margin: 0 auto;
}  
.book-a-table-form {
    height:300px;
    width:300px;
    z-index: 100;
    margin: auto;
    position: relative;
}
.container{
    max-width:1100px;
    margin: 0 auto;
    padding:50px
}
.img-fluid{
padding-top: 10%;

}
#bangor{
    width:100%
    ;padding:2%;
    height: 100px;
}
  .opening-times {
      display: grid;
      grid-template-columns: 25% 25%;
      gap: 20px;
      height: 100px;
      padding: 20px 5px 5px 40px;
      color: #28B4DF;
    }
 
.padding{
    padding-bottom: 2rem;
}
  .drink-container, li {
      padding:5px;
    }
  div.fish-position{
  background-color:#ADD8E6;
      border: 1px solid black;
    }

h3,h4 {
    color:#021a31
}
  
  
  THIS IS THE READ ME FILE AS INTENDED! 
  
  
  
  
  
  

Introduction:

Hodgey’s fish and chips is a fictitious restaurant business based loosely on a real life takeaway based in Hertfordshire UK that I worked for a as a delivery driver in the beginning six months of the covid-19 pandemic. The website offers information about the service provided, contact details, details of how to find the restaurant, a form for pre-booking a table and external links to third party delivery websites. The website consists of four pages. The home page with opening times and blurb of the business, a menu page, book a table page and a contact us page. 
   
![Screenshot 2021-10-29 at 16 30 51](https://user-images.githubusercontent.com/89813192/139572997-1e3c8531-becf-4cb4-a9c0-3cc7901c51d6.png)


UX:

My overall aim was to have a responsive website that gave a feel of the seaside through images and colour, this is the tone set throughout. I wanted it to be uncluttered and easy to navigate. 
A further aim was to clearly offer both parts of the restaurant and takeaway service and I have done this through a dedicated booking page and external links to delivery sites. 

Home page:

On the home I wanted a design that gave a quick synopsis of the service provided. A Navigation bar that was clear and was within the blue colour scheme that represents the seaside and a title that
clearly stated both restaurant & takeaway. In the centre is a jumbotron of a seafront in a coastal town in Devon called Brixham which I think is eyecatching for the user. Then underneath is useful information about opening times. 
   
   ![Screenshot 2021-10-30 at 20 12 21](https://user-images.githubusercontent.com/89813192/139573162-c668fb18-c7ed-4d04-b9d2-4f4f31623f45.png)
![Screenshot 2021-10-30 at 18 52 32](https://user-images.githubusercontent.com/89813192/139573166-625f94a5-3112-4dea-b373-268ed551cc06.png)






Menu Page: 

Throughout the design I used the CSS framework bootstrap to ensure that I was making a fully responsive website that would work from mobile device upwards. The framework was useful for placing the menu options It is split into the three items per row. Fish, burgers, pies then extras, drinks and desserts. I us used the bootstrap classes row and  col-sm-4 to achieve this. I deliberately wanted to keep this page as simple as possible and avoid images as a rule of thumb in the food world is that establishments are usually nicer if they don’t have pictures of the food next to the menu. 
   
   ![Screenshot 2021-10-30 at 20 13 01](https://user-images.githubusercontent.com/89813192/139573195-288259d4-29e5-4ffa-b998-99a2274be7df.png)

   

   
Book-a-table:

This page is a form for the user too interactive with in order to pre-book a table. To keep within the seaside image on this occasion I used a centered jumbotron of Bangor harbour in Wales. 
Underneath  this jumbotron is a centered form that I created which contains all of the information needed in order to book a table. Customers name, contact details times and date they want and amount of guests. I wanted to keep this form as wide as possible in order for the user to clearly see what input are needed in the form. In this case I used the classes row  and col-md-6 for placement. 
   
  ![Screenshot 2021-10-31 at 07 39 20](https://user-images.githubusercontent.com/89813192/139573287-6cd277cc-be2f-406e-9eb1-0943543951ff.png)
 ![Screenshot 2021-10-31 at 07 42 33](https://user-images.githubusercontent.com/89813192/139573363-ce2e3db6-5a19-44d4-9b86-835b5b4f7947.png)
![Screenshot 2021-10-31 at 07 43 20](https://user-images.githubusercontent.com/89813192/139573382-4380f219-3d8e-4a84-b5ea-630c815fa050.png)


Contact us. 

the main focus of the contact page for the user is the map of how to find the restaurant. For this and the address that is underneath and centered I put the address of the Fish & chip takeaway that I used to work for. I also put the address and contact number. In the footer there is a link to the newsletter so the restaurant has the option of creating a mail out if they would like. 
   
   
   ![Screenshot 2021-10-31 at 07 45 28](https://user-images.githubusercontent.com/89813192/139573434-5e90c31d-4d06-473e-9a90-702eaa652f79.png)
![Screenshot 2021-10-31 at 07 45 56](https://user-images.githubusercontent.com/89813192/139573445-8275afee-514c-4215-8481-89af205eb572.png)

   



Wireframe: 
The wireframe that I created was designed using Balsamiq Wireframes. I created the four pages that I wanted using the wireframe and where possible I stuck to this guide. Although there are some parts that I later decided against such as logo’s on the external links and using dropdown menus in the middle of the page for the menu section. The reason for this was that it didn’t fit the stylistic seaside scheme that I wanted. I also added an extra image in the Book a table page. 
   ADD WIREFRAME
[Wireframe for HTML and CSS project 1 .zip](https://github.com/samhodgson88/sh-fish-chips/files/7448294/Wireframe.for.HTML.and.CSS.project.1.zip)



The User Story

As a user I want the website to be easy to navigate. If I was local to the area I would be easily able find out the opening times so I could go to the takeaway myself. I can navigate all pages clearly and easily from the navigation bar. 

As a user I want to use a delivery service: I have included external links in the footer and in the header I have also provided internal links that go down to the footer for this. 

As a user I want to find out the location of the restaurant. This can be found on the contact us page. 

As a user I would like to book online. The form makes this possible. 

Testing. 

I tested the website that I created on Lighthouse and hear are the following results. The speed index came in at 2.5s accessibility received 93 out of 100. 

I also manually tested the responsiveness of the design in the google chrome developer tools where it work in phone tablet and desktop size. 

A recurring problem that I did not manage to resolve was a drop down box within the Nav bar. I had major issues around responsiveness with this and the dropdown box that would have had  the links to delivery services in would disappear at any below the desktop level of 1200px


Deployment 

The website has been deployed to git-hub pages as sh-fish-chips
![image](https://user-images.githubusercontent.com/89813192/139556364-f2a082af-8843-4e04-90c6-b172a15f291b.png)





 



 
  
   
