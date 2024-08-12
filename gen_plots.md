library("ggplot2")

ggplot(data=diamonds) +
  geom_point(mapping = aes(x=cut, y=price)) +
  ggtitle(paste(Sys.Date(), Sys.time()))
   



