        ## Event Source Architecture 
        
        * event source id we generally use to change any data on the database by using event.
        
        
        * For example, we have a person he's named "Robert" his address-1 is something in a database, usually people if they want to change his personality.
        
          address from the database they will easily change by not using any event, but by using an event we can add one event to change event so that we can
          
          reuse-that event when that type of production happens.
          
        
        * You can change the implementation of your model at any time, without the need for anything. we can change easily functionalities.
        
        
        * If you discover that some of your entities are in the wrong state you can replay the events that lead to that state one by one, to find out.
        
          which event is wrong. Once you found that you can check the code that produces this event and fix it so that the error does not happen again.
          
          
        * By using event source we can separate the code where you can de-bug or modify or find any but use this, it removes a lot of bundle code at a time.
        
        
        * Excellent testability - we can easily test our code for each event check-in weather it's going well or something.
        
        
        * We can add some features to this event source.
          
          * We can add a check balance on the account particular mentioned date.
          
          * We can check how many deposits are made in a particular year.
          
          * We can set the password incorrectly for more than 3 attempts.
          
          * We can be allowed more than some characters.

          * While your domain evolves you might want to evolve some event types. You still have to be able to deal with old events, so you can’t just remove them.
          
          * We can clear the shopping cart by user define event clicking.
          
          * When we use event sourcing do not put unnecessary data that never use any change by an event.

          * Each event has an event type or event name.

          * If you publish all your events then any other service can consume them and rebuild your whole state locally.

If you publish all your events then any other service can consume them and rebuild your whole state locallyat the event should be as small as possible.
        
       * Wse event sourcing when your model is complicated to create using more feature experience.
       
       ## Resouces

       * https://itnext.io/event-sourcing-explained-b19ccaa93ae4 (Google)

       * https://event-driven.io/en/category/?category=Event%20Sourcing (Google)

       * https://youtu.be/ck7t592bvBg (Youtube)