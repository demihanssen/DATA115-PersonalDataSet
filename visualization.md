# PersonalDataSet
crime <- read_csv("C:/Users/demia/Desktop/Data 115/CRIME1.csv")

guns <- read_csv("C:/Users/demia/Desktop/Data 115/firearms_licenses_usafacts.csv")

TotalG=guns$`Firearms licenses (Items)`

ggplot(data=guns, aes(x=Years, y=TotalG))+geom_line()+ggtitle("Gun Licenses In US 1975-2019")+xlab("Year")+ylab("Number Of Licenses")

ggplot(data=crime, aes(x=Year, y=Violent))+geom_line()+ggtitle("Violent Crime In US 1975-2019")+xlab("Year")+ylab("Frequency")
