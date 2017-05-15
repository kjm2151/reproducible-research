##There was a little problem because of the language setting of my desktop.
##when rerun the script please convert below portion 

data<- cbind(data, 
                      daytype=ifelse(data$weekday == "토요일" | data$weekday == "일요일", "weekend", "weekday"))



to

data<- cbind(data, 
                      daytype=ifelse(data$weekday == "saturday" | data$weekday == "sunday", "weekend", "weekday"))
