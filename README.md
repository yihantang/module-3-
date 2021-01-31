# module-3-pricatice to create data.frame
Name <-c("Jeb","Dpnald","Ted","Marco","Carly","Hillary","Berine")

ABC_politicalpollresults<-c(4,62,51,21,2,14,15)

NCB_politicalpollresults<-c(12,75,43,19,1,21,19)

results <- cbind(Name, ABC_politicalpollresults, NCB_politicalpollresults)

results.df <-data.frame(Name, ABC_politicalpollresults, NCB_politicalpollresults)

mean(results.df[,2:3])

