# Notes on datasets

For this challenge you must use the datasets in this folder.
Please ensure you have read the Terms of Use before using any of the datasets.
The complexity of this challenge is in understanding which data to use and how it links together and we have given some hints below to help you.
We are *not* expecting you to generate novel results from these datasets but to demonstrate how you would integrate datasets from the same study (SDY296 and SDY301) with datasets from different studies (SDY180) and how you would provide functionality including visualization, statistical analysis, and machine learning through a user-friendly platform.
Your prototype also does not need to show realistic analyses, we are interested in the functionality and its potential; not the results.

**Common files**

* Description: These files provide descriptive metadata that may be used by any of the three studies listed below, for example values for mapping variables between numeric codes and their actual values (e.g., [lk_race.csv](https://github.com/WellcomeIdeathon2023/infectious_disease_challenges/blob/main/correlates/datasets/Common%20files/lk_race.csv) shows the mappings between codes (1-9) and race).
* [link to data](https://www.immport.org/browser/?path=SDY180)
* [Terms of use](https://docs.immport.org/home/agreement/)

**SDY180**

* Study title: Systems scale interactive exploration reveals quantitative and qualitative differences in response to 2009-2010 Fluzone influenza vaccine and pneumococcal vaccine
* Study description: This is a systems immunology approach to study the immune response to seasonal influenza and 23-valent pneumococcal vaccination in healthy adults. Volunteers were vaccinated with either a single dose of seasonal influenza vaccine (2009-2010 Fluzone), a single dose of a pneumococcal vaccine; or a placebo (saline). Blood was taken at before vaccination and at multiple timepoints afterwards, depending on the assay used. Immune measurements included gene expression, serum antibody responses, cytokine analysis and flow cytometry. Gene expression, cytokine analysis, and serum antibody results are available.
* [link to data](https://www.immport.org/browser/?path=SDY180)
* [Terms of use](https://docs.immport.org/home/agreement/)

**SDY296 and SDY301**

* Study title: Systems Biology Approach to Analysis of Consecutive TIV Fluzone Influenza Vaccination in Healthy Individuals
* Study description: The overarching study measures the immune response to the influenza vaccine over three flu seasons (years). The goal is to develop improved vaccines to influenza by understanding the long-term immune response. The baseline knowledge generated in this project will be transferred to another study (not provided) where the immune response will be studied in patients with underlying immune system alternations. Healthy volunteers were vaccinated with the influenza vaccine and blood samples were taken before and after vaccination. Vaccination was repeated yearly. Immune measurements included gene expression, serum antibody responses, and flow cytometry. Only gene expression and serum antibody results are available. SDY296 contains the data for the 2011-2012 flu season (Year 1) and SDY301 contains the data for the 2012-2023 flu season (Year 2).
* [link to SDY296 data](https://www.immport.org/browser/?path=SDY296)
* [link to SDY301 data](https://www.immport.org/browser/?path=SDY301)
* [Terms of use](https://docs.immport.org/home/agreement/)

**Tips**

As this challenge has a lot of data to get through below are some tips to get you started

* A commercial assay was used to assess the antibody response to the pneumococcal vaccine. For comparison, the results have been combined with hemagglutinin and viral neutralisation assay results for antibody responses to influenza in the “serology” file, but you can find separate duplicate files for HAI and neut-Ab for influenza elsewhere.
* The SDY180/296/301-DR47_Tab contains .csv files that are needed to link different variables together e.g. which arm of the study received which vaccine; which volunteers (subject) were assigned to each arm and so on. These will be needed to link result measurements from different samples with metadata to identify immune signatures associated with vaccination.
* Luminex is a form of magnetic bead-based assay (mbba). The mbba.results file therefore contains the cytokine data.
