
<a href="https://play.google.com/store/apps/details?id=com.dogan.arabam&hl=tr"><img src="https://arbimg1.mncdn.com/assets/dist/img/tek-tur-large.gif"/>
</a>
## About Us ##

The arabam.com team, working with the mission to make buying and selling vehicles from the Internet much more reliable, easier and more comfortable, aims to improve the users experience with new functions continuously.
Those who want to sell their car or who want to buy a car can make transactions anytime, anywhere.

* 7 million users per month,
* Over 200 million page views,
* 7000+ car dealer members,
* 4 million individual members,
* 80% mobile traffic.


We are excited to see your motivation to join our team. So, we are trying to the best way for recruitment.  If you have questions, you can ask us when you want or need help. If there is a problem, please don't hesitate contact to us.


## Android Assignment ##

The purpose of this assignment is to create an app for Arabam's users and show them a list of adverts and show more details for each advert.

We are expecting you to implement a listing page and a detail page for the cars' adverts. On the listing page, you need to use the "listing" endpoint and show the advert list to the user. And, also you need to show a single-vehicle detail with the "detail" endpoint. You can find more information about endpoints in the Sandbox API section.


### Listing Page ###
* We expect to see the list of vehicles on the page.
* Vehicle image that returns from the listing response must also be shown in the list.
* We expect to see pagination is implemented on the list page
* The user should be directed to the detail page when selecting one of the results listed in the vehicle list.


##### Listing Page Bonus #####
* You can apply filters for the list page. For example,  `minDate `,  `maxDate`, or  `categoryId` etc. You can find it in our API docs. For the design concern, you can use bottomsheet, different fragment, or dialog for the filter page.
* You can apply sort with price, date, or year. We are supporting 3 different sort types.


### Detail Page ###
* We expect to see the selected vehicle on the page.
* Vehicle image that returns from the detail response must also be shown on top of the page.
* There is no obligation about detail page design and which information to be shown. You can configure this screen as you like.


##### Detail Page Bonus #####
* When a photo is tapped, it could be shown on a full screen.
* A component for viewing user information and CTA for calling the user's phone number.


### arabam.com SandBox API ###

You can see API details with different methods. We are providing 3 different solutions. You can use postman web or postman collection. Also, you can use our swagger page for the sandbox API.

* Web Postman -> https://www.postman.com/yusufcakmak/workspace/arabam-assigment/overview
* Postman Collection -> https://www.getpostman.com/collections/d0c83044d06639384b1b
* Swagger -> http://sandbox.arabamd.com/swagger/index.html


##### Listing Endpoint

This request will return list of adverts. With  `take` parameter you can decide how many adverts you will get.

curl -X GET "http://sandbox.arabamd.com/api/v1/listing?sort=1&sortDirection=0&take=10" -H "accept: text/plain"


##### Detail Endpoint

This request will return singe advert detail. With  `id ` parameter you can get the advert detail response.

curl -X GET "http://sandbox.arabamd.com/api/v1/detail?id=15207658" -H "accept: text/plain"


### Tips

* For pagination feature, you can use the  `take` and  `skip` parameters shown in the API docs.
* For vehicle image urls, you need to replace {0} with predefined resolutions. If you replace {0} with 800x600 you will get vehicle's image with 800x600 resolution. Inspect API docs carefully for the predefined resolution values.
* For the design concern, you can browse through our application or similar applications and be inspired by it. Be creative 🤸‍♂️


### Our Tech Stack
Our development language is Kotlin but we have legacy Java classes. We are following single activity & multiple fragments technique. We are expecting same approach. App should work above API level 21.

* Android Architecture Components
* ViewModel
* Paging
* LiveData
* DataBinding
* Dagger Hilt
* Retrofit
* RxJava
* Room

<br/>
<br/>

<p align="center">
If you have questions, you can ask to us when you want or need to help. If there is a problem, please don't hesitate about contact to us.
  </p>
<br/>
<p align="center">
<img src="https://media.giphy.com/media/l49JHz7kJvl6MCj3G/giphy.gif" width ="300" height="300"/>
</p>


