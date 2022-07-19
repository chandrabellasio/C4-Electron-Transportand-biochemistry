Please Ensure That You Have Installed R and R Studio Prior To Use

The C4 Model Can be run in one of two ways;

To Run The Model Using .csv Data:
	1. Open the template (TemplateData.csv) and change the input values
		NOTE: Only change the values in the values column.
	2. Save this as a new .csv file
	2. Open and run C4 Model.Rmd
	3. Follow the Prompts:
		When prompted to "Read Data From CSV File?" Type: Y
		When prompted for "File Folder Path =", Type the Path for the folder the .csv file is in
		When prompted for "File Name (Including File Type) =", type the FileName.csv
	4. Click Save
	5. Output Data Will Be Saved as C4 Model.nb.html

To Run The Model Using The Interactive App:
	1. Run C4 Model.Rmd
	2. When prompted to "Read Data From CSV File?" Type N
	3. The interactive App will run, allowing you to change the input parameters
		Various outputs are presented in different tabs at the top of the page


References/Citations:

  R Core Team (2022). R: A language and environment for statistical computing. R Foundation for
  Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.

App Generation was performed using the shiny_1.7.1 and DT_0.23 packages:

  Chang W, Cheng J, Allaire J, Sievert C, Schloerke B, Xie Y, Allen J, McPherson J, Dipert A,
  Borges B (2021). _shiny: Web Application Framework for R_. R package version 1.7.1,
  <https://CRAN.R-project.org/package=shiny>.

  Xie Y, Cheng J, Tan X (2022). _DT: A Wrapper of the JavaScript Library 'DataTables'_. R package
  version 0.23, <https://CRAN.R-project.org/package=DT>.



