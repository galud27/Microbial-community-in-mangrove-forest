# Data analysis for microbial community in mangrove forest

The scripts available here and data generated was used in a recent study: 

Erazo, N.G. and Bowman, J.S., 2021. Sensitivity of the mangrove-estuarine microbial community to aquaculture effluent: https://doi.org/10.1016/j.isci.2021.102204

You can download the original seqeunces here: 

The analysis for this project relied on the contribution of different bioinformatic pipelines, particularly paprica. Here you can find documentation on paprica and tutorials for microbial community structure and metabolic potential: https://github.com/bowmanjeffs/paprica

The paprica output can be very helpful to study the microbial community structure and function. In Erazo and Bowman 2021 we used: "2021_mangrove_study_bacteria.unique_tally.csv" to understand community structure and diversity. We used "2021_mangrove_study_bacteria.edge_data.csv" to obtain genamo parameters (e.g. genome size adn 16S copies),and "2021_mangrove_study_bacteria.path_tally.csv" to understand metabolic potential by examing different pathways. And we used "2021_mangrove_study_bacteria.ec_tally.csv" enzymes associated to the nitrogen cycle to undertand the impact of aqauculture in mangrove foprest. Here we used additional scripts that help us process enzyme data to extract Nitrogen enzymes. Here you can find more information on how to process the paprica output: https://github.com/avishekdutta14/downstream_paprica 

The scripts available here will help to perform 16S data analysis:
Alpha diversity,
Ordination analysis,
Deseq2 differential microbial abundance,
WGCNA network correlation, 
Analysis of environmental data
