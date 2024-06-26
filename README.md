## Free amino acids in African indigenous vegetables: Analysis with improved hydrophilic interaction ultra-high performance liquid chromatography tandem mass spectrometry and interactive machine learning

See [original article](https://www.sciencedirect.com/science/article/abs/pii/S0021967320310074) published in _J. Chroma A_. 

## Abstract

**A hydrophilic interaction (HILIC) ultra-high performance liquid chromatography (UHPLC) with triple quadrupole tandem mass spectrometry (MS/MS) method was developed and validated for the quantification of 21 free amino acids (AAs).** Compared to published reports, our method renders collectively improved sensitivity with lower limit of quantification (LLOQ) at 0.5 ~ 42.19 ng/mL with 0.3 μL injection volume (or equivalently 0.15 ~ 12.6 pg injected on column), robust linear range from LLOQ up to 3521 ~ 5720 ng/mL (or 1056 ~ 1716 pg on column) and a high throughput with total time of 6 min per sample, as well as easier experimental setup, less maintenance and higher adaptation flexibility. Ammonium formate in the mobile phase, though commonly used in HILIC, was found unnecessary in our experimental setup, and its removal from mobile phase was key for significant improvement in sensitivity (4 ~ 74 times higher than with 5 mM ammonium formate). Addition of 10 (or up to100 mM) hydrochloric acid (HCl) in the sample diluent was crucial to keep response linearity for basic amino acids of histidine, lysine and arginine. Different HCl concentration (10 ~ 100 mM) in sample diluent also excreted an effect on detection sensitivity, and it is of importance to keep the final prepared sample and calibrators in the same HCl level. Leucine and isoleucine were distinguished using different transitions. Validated at seven concentration levels, accuracy was bound within 75 ~ 125%, matrix effect generally within 90~110%, and precision error mostly below 2.5%.

Using this newly developed method, **the free amino acids were then quantified in a total of 544 African indigenous vegetables (AIVs) samples** from African nightshades (AN), Ethiopian mustards (EM), amaranths (AM) and spider plants (SP), comprising a total of 8 identified species and 43 accessions, cultivated and harvested in USA, Kenya and Tanzania over several years, 2013 ~ 2018.

**The AN, EM, AM and SP were distinguished based on free AAs profile using machine learning methods (ML)** including principle component analysis, discriminant analysis, naïve Bayes, elastic net-regularized logistic regression, random forest and support vector machine, with prediction accuracy achieved at ca. 83~97% on the test set (train/test ratio at 7/3). **An R Shiny based [interactive ML platform](https://boyuan.shinyapps.io/AIV_Classifier/) was constructed** for modeling train-test simulation and category prediction of unknown AIV sample(s). This new method presents a robust and rapid approach to quantifying free amino acids in plants for use in evaluating plants, biofortification, botanical authentication, safety, adulteration and with applications to nutrition, health and food product development.

## R Script Reference
This repository records the R script developed for data analysis and visualization and machine learning in the original publication ([see code and output](https://yuanbofaith.github.io/AfricanVegetables_AminoAcids/)). The R code has been developed with reference to [R for Data Science (2e)](https://r4ds.hadley.nz/), and the official documentation of [tidyverse](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- Data visualization with ggplot2 ([tutorial](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [data viz. gallery](https://www.databrewer.co/R/gallery)).

- [Data wrangling](https://www.databrewer.co/R/data-wrangling) with the following packages:
[tidyr](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure; [dplyr](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): the basic tools to work with data frames; [stringr](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings; [regular expression](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern; [purrr](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns); and [tibble](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.

## Follow me. Keep updated with my latest research

<table style="border-collapse: collapse; width: 100%; border: 0; border-spacing: 0;">
  <tr>
    <td style="border: none;" align="center">
      <a href="https://medium.com/@yuanbo.faith">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Medium_%28website%29_logo.svg" alt="Medium Logo" style="height: 20px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://x.com/yuanbogeneral">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/X_logo_2023.svg" alt="X Logo" style="height: 33px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://www.databrewer.co/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/DataBrewer.png" alt="DataBrewer Logo" style="height: 53px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://connects.catalyst.harvard.edu/Profiles/display/Person/193422">
        <img src="https://upload.wikimedia.org/wikipedia/en/1/18/Harvard_shield-Public_Health.png" alt="Harvard Public Health Logo" style="height: 50px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://orcid.org/0000-0003-0222-8095">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID Logo" style="height: 40px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://www.linkedin.com/in/bo-yuan-amazing/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn Logo" style="height: 33px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://harvard.academia.edu/BYuan">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Academia.edu_logo.svg" alt="Academia Logo" style="height: 15px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://scholar.google.com/citations?user=aFh0570AAAAJ&hl=en">
        <img src="https://static-00.iconduck.com/assets.00/google-scholar-icon-2048x2048-sjbhklt7.png" alt="Google Scholar" style="height: 35px; max-width: 100px; margin: 10px;">
      </a>
    </td>
  </tr>
</table>
