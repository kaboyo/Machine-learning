# Exploring-plasticity-of-the-tomato-seed-microbiome
Here, bacterial amplicon sequencing analyses of so far largest microbiome dataset involving 100 tomato cultivars were conducted to examine plant genetics and environmental factors influencing the seed microbiome composition.


# 0.0002, prevalence = 90/100
core.taxa.standard <- core_members(Bacteria_rel, detection = 0.0002, prevalence = 90/100);core.taxa.standard
######################################################################################################################
#A full phyloseq object of the core microbiota is obtained as follows:
pseq.core <- core(Bacteria_rel, detection = 0.0002, prevalence = .9);pseq.core

#Retrieving the associated taxa names from the phyloseq object:
core.taxa <- taxa(pseq.core);core.tax
