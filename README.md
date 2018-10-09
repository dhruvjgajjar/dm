# dm

Conversation opened. 1 read message.

Skip to content
Using Gmail with screen readers
Warning: Google prevented a suspicious attempt to sign in to your account using your password.Review activity now
×
Click here to enable
desktop notifications for Gmail.   
Learn more
  
Hide

4 of 273
prac 6n 7
Inbox
x

Dhruv Gajjar <dhruvjgajjar@gmail.com>
Attachments
Fri, Oct 5, 1:22 PM (4 days ago)
to me


Attachments area

> library(data.tree)
> g<-Node$new("v1")
> v2<-g AddChild("v2")
Error: unexpected symbol in "v2<-g AddChild"
> v2<-g$AddChild("v2")
> v3<-g$AddChild("v3")
> v4<-v3$AddChild("v4")
> v5<-v4$AddChild("v5")
> print(g)
       levelName
1 v1            
2  ¦--v2        
3  °--v3        
4      °--v4    
5          °--v5
> plot(g)
Warning message:
package ‘bindrcpp’ was built under R version 3.4.4 
> library(data.tree)
> g<-Node$new("v1")
> v2<-g$AddChild("v2")
> v3<-g$AddChild("v3")
> v4<-v3$AddChild("v4")
> v5<-v3$AddChild("v5")
> print(g)
   levelName
1 v1        
2  ¦--v2    
3  °--v3    
4      ¦--v4
5      °--v5
> plot(g)
> q()
> 
prac 6 n 7.txt
Displaying prac 6 n 7.txt.
