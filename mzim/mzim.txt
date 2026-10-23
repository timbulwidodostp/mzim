# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Marginalized Zero-Inflated Models for Count Data Use mzim With (In) R Software
install.packages("remotes")
remotes::install_github("cliattx/mzim")
library("mzim")
# Estimate Marginalized Zero-Inflated Models for Count Data Use mzim With (In) R Software
mzim = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mzim/main/mzim/mzim.csv",sep = ";")
mzim <- mzim(count_formula = mzim ~ mzim_1 + mzim_2, zi_formula = ~ mzim_1 + mzim_2, data = mzim, family = "zinb")
summary(mzim)
# Marginalized Zero-Inflated Models for Count Data Use mzim With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished