# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# streamlined nonlinear regression Use TEfit (TEfits) With (In) R Software
install.packages("remotes")
remotes::install_github("akcochrane/TEfits")
library("TEfits")
TEfit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/TEfit/main/TEfit/TEfit.csv",sep = ";")
# Estimation streamlined nonlinear regression Use TEfit (TEfits) With (In) R Software
TEfit <- TEfit(TEfit[,c('Tefit_1','Tefit_2')])
plot(TEfit,plot_title='Time-evolving fit of artificial data')
summary(TEfit)
# streamlined nonlinear regression Use TEfit (TEfits) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished