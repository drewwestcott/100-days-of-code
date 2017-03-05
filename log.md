# 100 Days Of Code - Log

### Day 1: January 3, Tuesday

**Today's Progress**: Completed some code I have been putting off on my watchOS project.

**Thoughts** I've have a pretty good functioning App with several bugs in it. I would say I am at that 80% done with the feeling like the next 20% will take as long as the first 80 did. Today's hour gave me the excuse to sit down and start coding on the project again. I have sorted two issues out.

**Link(s) to work**
1. [steps-tracker](https://bitbucket.org/drewwestcott/steps-tracker/commits/95a57534f2bbc32b7ab3f23c30bc63cb43662c85)

### Day 2: January 4, Wednesday

**Today's Progress**: More of the 20% work for my watchOS project and started investigating alogithms exercises (today's from weheartswift).

**Thoughts** For the first exercise on weheartswift I was going to iterate over the string and take each letter in turn to append to a new string, then I remembered seeing swifts array reverse() method. So started down that line instead. The second exercise I coded in a basic fashion and satisfied all the tests. However, the solution was an much more elegant way to code it.

**Link(s) to work**
1. [steps-tracker](https://bitbucket.org/drewwestcott/steps-tracker/commits/8ebd41225af3a88eab4caa65b9b1259eb4bbcfb3)
2. [exercises](https://github.com/drewwestcott/we-SwiftExercises/commit/3b96954c79bb11f717a0d3b0b884d3217d476050)

### Day 3: January 5, Thursday

**Today's Progress**: Completed a couple more alogithms exercises (today's from weheartswift).

**Thoughts** Today has been interesting. I managed to code the exercises quite easily and got very close to the suggested solution, with my own code feeling slightly more refined. The second exercise on palindrome landscape took me a while to understand the brief. My first try did not satisfy the tests, but after reading the hints a couple of time I managed to satisfy the test and like my code.

**Link(s) to work**
1. [exercises] (https://github.com/drewwestcott/we-SwiftExercises/commit/cfa53143a9c7c3765f41f93e4e263f2603eaa362)

### Day 4: January 6, Friday

**Today's Progress**: Completed a couple more  exercises (today's again from weheartswift).

**Thoughts** Wow, I had to think about this one. I nearly wrote code to test all numbers up to i each time, but after reviewing the idea Prime Numbers realised I could use square roots in the equation.

**Link(s) to work**
1. [exercises] https://github.com/drewwestcott/we-SwiftExercises/commit/aecf99585c1f2e834921288abeec1f0654daadf6

### Day 5: January 7, Saturday

**Today's Progress**: Debugging. 

**Thoughts** Stuck with a tutoiral I had been following outside of hour of code. Decided to try and debug the 'selector sent to instance bug' so I can continue with the tutorials. Good practice working through break points and google searches.

**Link(s) to work**
1. [project] https://bitbucket.org/drewwestcott/set-capture/commits/5c68de351f91f6358553a79445f0ef0ca638a7fd

### Day 6: January 8, Sunday

**Today's Progress**: First Pull Request. 

**Thoughts** Have been getting used to commits and branching in my git. Today I decided to set the Master branch? to be the current state of development. Managed it and have given the App to a user to test.

**Link(s) to work**
1. [project] https://bitbucket.org/drewwestcott/steps-tracker/pull-requests/1/watch-connectivity-and-complications#comment-None

### Day 7: January 10, Tuesday

**Today's Progress**: Code Kata. 

**Thoughts** Realised I am going to need a settings screen for my project before it goes live. Couldn't quite remember how do dismiss the on the screen keyboard once a user finished with a text field, so created a project to practise just that.

**Link(s) to work**
1. [code-kata] https://github.com/drewwestcott/Target-Setting/commit/0b050351c0a8baf7234ec8dd4cfd8f4eefb5c9ee

### Day 8: January 11, Wednesday

**Today's Progress**: Test animation. 

**Thoughts** Wanted to put text over the top of an image/animation for a WatchOS App. Did some research to see if it was possible and then practiced by creating a small App to prove it would work.

**Link(s) to work**
1. [project] https://github.com/drewwestcott/watchOS-background-test/commit/c2bb4d34d074a46e46498e214ad7ead289cfc924

### Day 9: January 12, Thursday

**Today's Progress**: Exercise. 

**Thoughts** Read the Nobody's Decision exercise from weheartswift.com. Took me a little bit of time to work out an approach, but code past all tests.

**Link(s) to work**
1. [exercise] https://github.com/drewwestcott/we-SwiftExercises/blob/master/decisions.swift

### Day 10: January 13, Friday

**Today's Progress**: Made Changes to Step Tracker project based on user feedback. 

**Thoughts** Feedback suggested some of the information displayed was confusing, so have adjusted based on feedback.

**Link(s) to work**
1. [project]https://bitbucket.org/drewwestcott/steps-tracker/commits/9ff08212034bc68c6c9d6d6db6bbc98d2ada4d7b

### Day 11: January 14, Saturday

**Today's Progress**: Updated Graphics in my App and refactored the complication code. 

**Thoughts** Feels like I'm getting close to being able to beta the App.

**Link(s) to work**
1. [project]https://bitbucket.org/drewwestcott/steps-tracker/commits/4422b6436b8f95adcd8bbb5f3c7d0887599a0e9d

### Day 12: January 15, Sunday

**Today's Progress**: Tracked down a bug introduced by yesterday's code. 

**Thoughts** Complications stopped reliably updating, so had to check code changes yesterday and work out what was wrong. Decided that the scheduleBackgroundRefresh() needed to be outside my closure.

**Link(s) to work**
1. [project]https://bitbucket.org/drewwestcott/steps-tracker/commits/23ac458574b6bc716bf5ec015cbac85580cba932

### Day 13: January 16, Monday

**Today's Progress**: Worked on my App again. 

**Thoughts** Managed to set up a settings screen and create a Popover Modal to present it.

**Link(s) to work**
1. [project]https://bitbucket.org/drewwestcott/steps-tracker/commits/a130043aef7713e821c767f48571c5b7936575e3

### Day 14: January 17, Tuesday

**Today's Progress**: Code Kata for Watch Connectivity. 

**Thoughts** Really not got the code needed to connectivity between Watch App and iPhone App in my head, struggled to remember what was needed.

**Link(s) to work**
1. [code-kata]

### Day 15: January 18, Wednesday

**Today's Progress**: Code Kata for Watch Connectivity. 

**Thoughts** Got on much better today, did some reading after yesterday and managed to get the Apps talking to each other. Downside for Apple Watch App is that it does need to be running for the communication to work in the fashion I chose. But good exercise non the less.

**Link(s) to work**
1. [code-kata] https://github.com/drewwestcott/Request-Update/commit/23c4b5c8d2b649625c24405c702c6df79688fb06

### Day 16: January 19, Thursday

**Today's Progress**: App Project. 

**Thoughts** Used the learning from yesterdays code kata to allow my projects iPhone App to set up targets and communicate changes made to the watch App.

**Link(s) to work**
1. [project] https://bitbucket.org/drewwestcott/steps-tracker

### Day 17: January 20, Friday

**Today's Progress**: Exercise and App Store. 

**Thoughts** started a coding exercise and worked on how to submit Apps to the App Store.

**Link(s) to work**
1. [project] https://bitbucket.org/drewwestcott/steps-tracker

### Day 18: January 22, Sunday

**Today's Progress**: Exercise from weheartswift.com. 

**Thoughts** Thought this one would be a quick one and I would move on to another, but brought up lots of questions for best ways to search for a string and search an array. I even tried thinking of how to code without importing Foundation but thought that was a waste of time.

**Link(s) to work**
1. [exercise] https://github.com/drewwestcott/we-SwiftExercises/commit/fb485a123d13d45d3df7cc30fb376e5d6482ecdb

### Day 19: January 23, Monday

**Today's Progress**: Project. Parse A CSV 

**Thoughts** Started to wrtie a project to read in the contents of a CSV File. Didn't want to just copy and paste though so have been reading the Apple Documentation and writing code from that.

**Link(s) to work**

### Day 20: January 24, Tuesday

**Today's Progress**: Project. Parse A CSV 

**Thoughts** Started to wrtie a project to read in the contents of a CSV File. Didn't want to just copy and paste though so have been reading the Apple Documentation and writing code from that.

**Link(s) to work**
1. [project] https://github.com/drewwestcott/CSVparsing/commit/25dc753f5089a7d3b5937001fbcf23b277e32c9a

### Day 21: January 25, Wednesday

**Today's Progress**: Refactored code from yesterday: Parse A CSV 

**Thoughts** Started to wrtie a project to read in the contents of a CSV File. Decided to make code a bit more portable and cleaner. Refactored to one function.

**Link(s) to work**
1. [project] https://github.com/drewwestcott/CSVparsing

### Day 22: January 27, Friday

**Today's Progress**: Fixed a bug in my beta project 

**Thoughts** Had tried to tidy up my code before submitting to Test Flight, and realised as people started to test it that the notifications were not firing. Tracked down error and corrected.

**Link(s) to work**
1. [app] https://bitbucket.org/drewwestcott/steps-tracker/commits/e544b0fdf8530bf5b74455745a21c42c78fb43b5

### Day 23: January 28, Saturday

**Today's Progress**: Test modal presentation of a view controller 

**Thoughts** wanted to understand presenting a view over the top of another, whilst still being able to see the original view below. Ended up with some crashes which took time to debug. Turned out I renamed the viewcontroller and it hadn't been set correctly in the Identity Inspector

**Link(s) to work**
1. [app] https://bitbucket.org/drewwestcott/steps-tracker/commits/e544b0fdf8530bf5b74455745a21c42c78fb43b5

### Day 24: January 29, Sunday

**Today's Progress**: Playing with date code 

**Thoughts** wanted to understand how to calculate the number of days since a date. Ran into a problem with saving to userdefaults in Playgrounds. But decided to work around that by manually creating a start date. Will be using this in my next project.

**Link(s) to work**
1. [app] https://github.com/drewwestcott/we-SwiftExercises/commit/85b4fe5697e7889e06011d8aee223e2c1550b483

### Day 25 - 26: February 6-7, Monday & Tuesday

**Today's Progress**: Playing with downloading a file using iOS and swift 

**Thoughts** Feel off the horse a bit, as couldn't think what to code next. Started to think of some new App ideas and so breaking them down into parts that will be needed. Managed to get file to download on iPhone which was exciting, but couldn't get the code to work for the Apple Watch at the moment.

### Day 27: February 8, Wednesday

**Today's Progress**: Testing Local Notifications. 

**Thoughts** trying to explore local notifications on iOS and how they react to actions on the notification message.

**Link(s) to work**
1. [test-app] https://github.com/drewwestcott/swift3-local-notification-test/commit/53dc69f4eadc3c553c5f89531c38de3a31da4d35

### Day 28: February 9, Thursday

**Today's Progress**: Encoding Class for UserDefaults. 

**Thoughts** exploring encoding Custom Class to store in UserDefaults.

**Link(s) to work**
1. [test-app] https://github.com/drewwestcott/Centering-Thoughts/commit/22e96fc2c7b03a354cc57a5f8cf186b7bc00ed35

### Day 29: February 11, Saturday

**Today's Progress**: Trying to use UIPageViewController. 

**Thoughts** Need to set up some instruction pages when an App is first launch. Trying UIPageViewController as a way to apprach this. For some reason only first page is showing. Full of head cold though so debugging will be tomorrow's hour.

1. [test-app] https://github.com/drewwestcott/onBoarding/commit/ffa168cb041d7c01e976e48ffda37b9c6f42db0b

### Day 30: February 12, Sunday

**Today's Progress**: Trying to use UIPageViewController. 

**Thoughts** Debugged error: Mistyped VC name in array. Also added extra page to the UIPageViewController. Also made the UIPageViewController present modally over an existing view as this is the most likely use I will have for it.

1. [test-app] https://github.com/drewwestcott/onBoarding/commit/ffa168cb041d7c01e976e48ffda37b9c6f42db0b

### Day 31-32: February 14-15, Tuesday - Wednesday

**Today's Progress**: Testing Playing Extended Audio Content. 

**Thoughts** Added a mp3 file to my App to test playing a resource in the background. Got really messed up between previous code I was writing to download files. So in the end decide to start a fresh and just focus on audio in the background for Apple Watch. Lesson learned, don't over complicate things at this stage

1. [test-app] https://github.com/drewwestcott/audioPlay/commit/c31da392530314bcf71c36f08491b798cf4e61a8

### Day 33-34: February 17-18, Friday - Saturday

**Today's Progress**: Testing downloading in background on watchOS. 

**Thoughts** Could not get the code to download. Appeared to be starting the session correctly but never completed a download. Try to put breakpoints in to debug the code. Then today started to change the code to try and get a successful download. All in all feeling like i have hit a wall today.

1. https://github.com/drewwestcott/watchOSbackgroundDownload/commit/ae2616902f34baaf6c4127b3d9acc9609bf6d5d9

### Day 35: March 1, Wednesday

**Today's Progress**: Parsing a set feed to test getting data. 

**Thoughts** Fallen behind a bit as can be seen from the dates, but going to try and be more consistent now.

1. [test-app] https://github.com/drewwestcott/xmlParse/commit/ea5c4f4f8a46a3a1f4197603fb6e1981e28e43c7

### Day 36: March 2, Thursday

**Today's Progress**: Refactored parsing and tested with second feedURL 

**Thoughts** Found a very useful Swift 3 method 'trimmingCharacters(in: .whitespacesAndNewlines)'

1. [test-app] https://github.com/drewwestcott/xmlParse/commit/3f24a789ef44471107f1d73097cd67818743a256

### Day 37: March 3, Friday

**Today's Progress**: Feed parsed and then details sent to second ViewController 

**Thoughts** managed to get the feed to select a podcast and then display details and download the podcast in a second view controller.

1. [test-app] https://github.com/drewwestcott/xmlParse/commit/3f24a789ef44471107f1d73097cd67818743a256

### Day 38: March 4, Saturday

**Today's Progress**: Working with WKInterfacePicker 

**Thoughts** adding a settings view to my Watch App 

1. [beta-app] https://bitbucket.org/drewwestcott/steps-tracker/commits/7375ba2ad0aed8e28fac664102763b97aedaa8b7
