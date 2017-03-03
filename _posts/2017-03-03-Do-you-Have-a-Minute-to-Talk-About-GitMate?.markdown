# Do you Have a Minute to Talk About GitMate?
*by Sebastian Latacz*

Picking up where we left off with the [previous entry](http://blog.gitmate.io/gitmate/2017/02/17/4-Steps-to-GitMate.html), this entry will show you how we use Customer Development, which problems occurred and some of the data we’ve gained.

We started at step one of Customer Development: Validating that the problem we are trying to solve is “worth solving”. You do that by interviewing a person from your potential target group, trying to find out whether the person is experiencing the problems you are assuming. It is important to understand, that this interview is not about your product, it’s about understanding the potential customer's problems and workflow. Oftentimes, you don't even lose a word about your features.

With our business model written down and the hypotheses for our experiment phrased out, we were ready to interview software developers. Then, our first Problem occurred: Finding interview partners. We reached out to our networks and developer groups, but it was surprisingly hard to schedule interviews. We only got 7 interviews within 6 weeks, a rate way too low for the fast moving startup/software development environment.

I feel that this is at least partly due to the culture in Germany. If you have a meeting outside your work schedule, it's usually only for lunch: There is only one chance per day to meet a person. Also, it's unusual to meet people you don't know yet. Quite often people think that you are going to try to sell them something.

The outcome of the interviews was quite diverse. People weren't experiencing the problems as much as we thought. For Example, one assumption was, that people spend 50% of their time on code review (based on our work at coala). Within our 7 interviewees, it was only 11% in average, with a maximum of 30% and a minimum of no review at all. Most people didn't feel like they were spending too much time on review. Also, the quality issues we were experiencing at coala (an open source environment) were expected to be solved by the developers themselves in a commercial environment.

At this point, according to Customer Development, we would have to formulate new problem hypothesis and test them again. Of course, this makes sense: The best products resolve a pain people have. But at our rate, we would go on with this forever.

On the other end, FOSDEM 2017 was coming up and with that a great chance to talk to all kinds of developers. Within a conference, you can't ask them to sit down for a 30-minute interview, but you can show them some features and receive feedback. According to the Customer Development approach, this would be in the next step called solution interview, after verifying your problems. But since we were going to FOSDEM with coala anyway, we might just use the chance and do some solution interviews.

We created a slideshow with mockups showing how the features would work (a visual MVP) and prepared a form for collecting the feedback. Within 2 days at FOSDEM, we were able to conduct 19 solution interviews. And we’ve gained some valuable insights.

One crucial assumption was, that our potential customers use GitHub not only for open source projects, but also for commercial software development. We weren't quite sure about this and it felt a like the GitHub competitor BitBucket was more commonly used for commercial software development in europe. Within our sample 45.5% use GitHub for their projects, while only 18.2% use BitBucket. Do our potential customers use GitHub? Check!

Also we tested 3 features: Our original idea the GitMate comments, an early stage bug detector we call Linespots and automated management for Issues/Pull Request. We asked the interviewees to rate each on a scale from 1 (useless) to 5 (useful). Also we asked them whether they would pay 10$ per month and user for the particular feature offered as a service.

![alt text](https://raw.githubusercontent.com/GitMateIO/GitMateIO.github.io/master/_posts/1703FirstInterviewFindings.png "First GitMate Interview Findings")

The people rated the comments 3.6 in average. However the feature didn't convince them enough to pay for it: Only 37% responded with “Yes”. Linespots performed best in the rating (4.2) and willingness to pay (58%). While the Issue/Pull Request management performed worst (3.1) in the rating and hardly anybody would pay for that (16%).

So without any programming being done, we were able to gain actual data. We verified assumptions about our customers and we got some ideas on our feature prioritization: We should concentrate on Linespots, the comments could also work and we should drop the Issue/Pull Request management.

On the other hand we have noticed, that we skipped ahead on the problems. For example we haven’t verified the problems we are solving with Linespots. And since people are more willing to buy something that solves a significant problem than rather something which is just nice to have, we should verify that.

Right now we are evaluating whether the next step will be to validate the problems or to keep testing our solution. We will keep you updated with our next blog entry!

#### Side note
I feel like not many startups in Germany are actually practicing methods like Customer Development, Lean Startup or Disciplined Entrepreneurship. If you are, I would like to get in contact with you! If you know any company practicing these methods please forward this blog entry (or side note). If you do practice these methods [contact me](mailto:sebastian@gitmate.io)! (Or [join the Meetup!](https://www.meetup.com/de-DE/Lean-Startup-Hamburg/events/237908473/))




#### Footnotes

*Linespots is the result of the research by our highly skilled colleague [Maximilian Scholz](https://github.com/sims1253)*

*The Lean Startup is a trademark and service mark owned by Eric Ries.*
