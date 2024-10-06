## Research Data Analyst/Consultant

### Education 
Psychological Sciences, MA (_MAY 2025_)
Psychology, BA (_MAY 2021_)

### Work Experience
Research Data Consultant @ Appalachian State University
- Big Impact Project 1
- Big Impact Project 2

### Projects
#### Weight Bias and Health Sciences Education 
- **Main Question:** Do the weight biases of health care educators covary with their approaches to teaching about weight and health?
- **Data Acquisition:** Health sciences educators were recruited through a cluster sampling method (_three universities in each state that have a health sciences program were randomly picked_)
-   Educators were asked to complete a Qualtrics survey that measured weight bias, curriculum type, and demographics.
-   The data set was cleaned using excel (_incomplete surveys were removed for consent concerns_)
-   R studio was used to make composite variables,(_combining variables into one composite score_), run alphas, and complete descriptive and inferential statistics.
-   R script: #Creating a composite variable in R
    #Checking alpha first to make sure the items 
  alpha(calyope[,c('UMBFAT1','UMBFAT2','UMBFAT5','UMBFAT7','UMBFAT8','UMBFAT11','UMBFAT12','UMBFAT13','UMBFAT14',
                'UMBFAT15','UMBFAT16','UMBFAT17','UMBFAT18','UMBFAT19','UMBFAT20')])
    #Overall scale score variable
    calyope$UMBFAT_SCALE <- rowMeans(calyope[,c('UMBFAT1','UMBFAT2','UMBFAT5','UMBFAT7','UMBFAT8','UMBFAT11','UMBFAT12','UMBFAT13','UMBFAT14',
    'UMBFAT15','UMBFAT16','UMBFAT17','UMBFAT18','UMBFAT19','UMBFAT20')], na.rm=TRUE)

#### Weight Stigma and Perceptions of Fitness Influencers 
- 

