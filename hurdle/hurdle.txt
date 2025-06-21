# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Hurdle Models for Count Data Regression Use hurdle (pscl) With (In) R Software
install.packages("remotes")
remotes::install_github("brechtdv/rineq")
library("rineq")
hurdle = read.csv("https://raw.githubusercontent.com/timbulwidodostp/hurdle/main/hurdle/hurdle.csv",sep = ";")
# Estimation Hurdle Models for Count Data Regression Use hurdle (pscl) With (In) R Software
hurdle <- hurdle(art ~ fem + mar+ kid5 + phd + ment, data = hurdle)
summary(hurdle)
# Hurdle Models for Count Data Regression Use hurdle (pscl) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished