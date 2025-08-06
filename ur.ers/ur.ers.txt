# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Elliott, Rothenberg and Stock Unit Root Test Use ur.ers (urca) With (In) R Software
install.packages("urca")
library("urca")
ur.ers = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ur.ers/main/ur.ers/ur.ers.csv",sep = ";")
# Estimation Elliott, Rothenberg and Stock Unit Root Test Use ur.ers (urca) With (In) R Software
ur.ers <- na.omit(ur.ers[, "ur.ers"])
ur.ers <- ur.ers(ur.ers, type="DF-GLS", model="const", lag.max=4)
summary(ur.ers)
# Elliott, Rothenberg and Stock Unit Root Test Use ur.ers (urca) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished