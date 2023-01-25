# Lab-1_-202001060-

				                                                                IT-314  (Lab-1)

Q1) identify the FRs and NFRs.

Ans)  

FRs: 
1. User registration:  A member of the institute should be registered for the LIS and on successful registration provided with user credentials which will be used for any transactions(issue or return).
2. User login: A registered user can login in the LIS using his user credentials.On login, the user can use different features such as 
  a. Search book: User can search the book/s he wants that are available in the institute’s library. He can search for books of particular interest like books written by some author the user likes, on a particular subject etc.
  b. Issue book: The user can issue the book he wants if available in the library, no other user has currently issued the book and the user has not reached the limit to issue the book.
  c. Mark for issue: If the book is already issued the user can use this feature to get the book issued when the book gets available in the library. He has to register using his user credentials that are registered otherwise the book will not be issued. The user who marked for issue first would automatically get the book issued. He will get the notification to confirm the issue of the book. Once he agrees he will get the book and if he denies the other user waiting will get the chance.
  d. Return book: The issued books should be returned after a certain time period. The users who issue the book should get the least date of returning the book through his details registered. Once the book is returned, the LIS should show the update and the users who had used the feature mark for issue should get the book.
  e. Reissue book: If the book issued does not have a mark for issue on it then the user can apply to reissue the book.
  f. Request book: If the book user wants is not available in the library, then he can request for that book to be made available in the library. If a particular book has many users requesting for the book then it will be made available in the library.
  g. Add/Remove book: The librarian can add or remove a book according to the requests of the users and the utilization of the book.
  h. Notification: If there are any important announcements to be made, they are delivered to users through this feature. When new books are added, library timings are changed, library closed for a certain time period etc announcements can be made.
  
NFRs:
1. It should be accessible for 24x7.
2. Many users should be able to access it at the same time.
3. Should be accessible with only institute LAN.
4. Developed using HTML 5.
5. This LIS web application should be operable through browsers like firefox, google chrome, internet explorer, opera etc.
6. The announcements related to books such as particular books added to library or returned etc should be made in real time. Also this should be done by the LIS. Only important announcements should require the librarian.
7. The user should get the notification to return the book on the least date to return the book so if the user has forgotten he will be reminded.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q.2. Identify scope, features and non-functional aspects of the following problem.
Ans)  
Scope:
As a large number of people suffer from hearing loss, our mobile application can help in preventing many accidents from happening. Mobile phones can be linked with wearable hearing devices, so the user won’t miss to notice important key sound events such as car horns, fire alarm,baby etc. 

Features:
Our app uses artificial intelligence, so it can predict the priority of the sounds it hears and recognizes.
It should come with the functionality of being designed with different modes for different environment like driving,working etc.
If the app finds key sounds that are related to accidents like explosion sounds,collision sounds etc nearby then it alerts the user.
The app will have the feature to recognize the voice of the user and also perform certain simple actions.
It works in real time and is optimized for android with low-latency.
It can also monitor what kind of sound the user listens to most and provide suggestions as to which mode might suit the user most.

Non-functional aspects:
It should not consume much battery.
Should be very easy and simple to us so even people with less knowledge of software can operate it.
Its response should be fast.
