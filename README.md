# collab-whoi
Collaborating with Github at whoi

ggplot(data=se)+
geom_point(aes(x=year,y=visitors,color=park_name))+
  facet_wrap(~state,scales="free")+
  theme(axis.text.x=element_text(angle=90))

Mary is adding something.