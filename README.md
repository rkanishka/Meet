user stories

1) As a user,I should be able to filter events by city,So that I can see a list of events taking place in that city.
 2)As a user ,I should be able to show/hide events details,so that can have control over the amount of information display.
   3)AS a user ,I should specify number of events,so that I can organized events and I can find events very quickly from list.
   4) As a user, I should able to use app when offline , so that I can access any information about event  even without internet.
   5) As a user , I should able to add app shortcut to the home screen , so that I have easy access.
   6) As a user , I should able to display charts visualizing event deatails, so that It is easy to understand.
  

scenario
1)GIVEN:The event element has show detail button
WHEN:user click on it
THEN:all event detail displayed

2)GIVEN:The event element has hide deatails button
WHEN:user click on it
THEN:all the details  should collapsed

3)GIVEN: user click on city name from list
WHEN:select the city
THEN:number of events display user should see specific number of events at a time which is 32

4)GIVEN:user open the app shortcut on screen 
WHEN: access any information about event 
THEN:user can access any information about event in offline and get error when change search setting(city , number of events)

5)GIVEN: user click on icon
WHEN:click on display chart icon 
THEN:user can see chart with number of upcoming events in each city
