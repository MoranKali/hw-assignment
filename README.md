# akeyless-hw
Hey guys!

A few notes about my solution:

* I used helm to deploy both grafana and prometheus. I wish I used a different method for prometheus, it's been a hassle to configure.
* I installed K6 via choco, instead of running it as a deployment, like you have, in order to save time.
* I used a demo app from https://github.com/brancz/prometheus-example-app/tree/master, but connected it to my existing prometheus server using the pod-monitor and service-monitor jobs. 
* I hadn't managed to configure the prometheus remote writer yet, because of the way I deployed it. I might be able to get it to work, or just scrap this prometheus deployment and try again using the operator.
* I was able to run a pretty nifty load test with k6, but not export its results to prometheus. I'll share a printscreen anyway.
* I did not spend too much time on the grafana dashboards, as I planned to do this last.

Overall I quite enjoyed this HW assignment. 
I did not have a work env configured on my pc, so unfortunately I spent a bit too much time on getting that going, and dealing with windows issues.
Anyway, I might keep tinkering with this over the weekend, it's a fun little project.
