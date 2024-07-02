# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Regression-based inequality decomposition Use dineq_rb With (In) R Software
install.packages("dineq")
install.packages("munsell")
library("dineq")
dineq_rb = read.csv("https://raw.githubusercontent.com/timbulwidodostp/dineq_rb/main/dineq_rb/dineq_rb.csv",sep = ";")
# Estimation Regression-based inequality decomposition Use dineq_rb With (In) R Software
dineq_rb <- dineq_rb(income~hh_structure+education+domicile_size+age_cat,weights="factor",dineq_rb)
dineq_rb
# Regression-based inequality decomposition Use dineq_rb With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished