---
knit: "bookdown::render_book"
title: "The Epidemiologist R Handbook"  
description: "The Epi R Handbook is a R reference manual for applied epidemiology and public health."
author: "the handbook team"
date: "2021-08-31"
#url: 'https://github.com/nsbatra/Epi_R_handbook'
#twitter-handle: 
#cover-image: images/R_Handbook_Logo.png
site: bookdown::bookdown_site
# output: bookdown::gitbook:
#      config:
#           sharing:
#                twitter: yes
#                facebook: yes
#                whatsapp: yes
#                github: yes
documentclass: book
---

# output: bookdown::gitbook:

Placeholder


## R for applied epidemiology and public health {-}  
## How to use this handbook {-} 
## Acknowledgements {-}  
### Contributors {-}  
### Funding and support {-}  
### Inspiration {-}  
## Terms of Use and Contribution {-}  
### License {.unnumbered} 
### Citation {.unnumbered}
### Contribution {.unnumbered}  

<!--chapter:end:index.Rmd-->

# (PART) About this book {.unnumbered}


<!--chapter:end:new_pages/cat_about_book.Rmd-->


# Editorial and technical notes { }

Placeholder


## Approach and style
### R packages {.unnumbered}
### Code style {.unnumbered}
### Nomenclature {.unnumbered}  
### Notes {.unnumbered} 
## Editorial decisions  
## Major revisions  
## Session info (R, RStudio, packages)  

<!--chapter:end:new_pages/editorial_style.Rmd-->


# Download handbook and data  

Placeholder


## Download offline handbook  
### Use download link {.unnumbered}  
### Use our R package {.unnumbered}  
## Download data to follow along  
### Use our R package {.unnumbered}  
### Download one-by-one {.unnumbered}  
#### Case linelist {.unnumbered}
#### Malaria count data {#data_malaria .unnumbered}  
#### Likert-scale data {.unnumbered}  
#### Flexdashboard {.unnumbered}  
#### Contact Tracing {.unnumbered} 
#### GIS {.unnumbered}  
#### Phylogenetic trees {.unnumbered}  
#### Standardization {.unnumbered}  
#### Time series and outbreak detection {#data_outbreak .unnumbered}  
#### Survey analysis {#data_survey .unnumbered}  
#### Shiny {#data_shiny .unnumbered}  

<!--chapter:end:new_pages/data_used.Rmd-->

# (PART) Basics {.unnumbered}


<!--chapter:end:new_pages/cat_basics.Rmd-->


# R Basics {}

Placeholder


## Why use R?
## Key terms  
## Resources for learning {#learning}  
### Resources within RStudio {.unnumbered}  
### Cheatsheets {.unnumbered}
### Twitter {.unnumbered}  
### Free online resources {.unnumbered}  
### Languages other than English {.unnumbered}  
## Installation  
### R and RStudio {.unnumbered}  
### Other software you *may* need to install {.unnumbered} 
#### TinyTex {.unnumbered}  
#### Pandoc {.unnumbered}
#### RTools {.unnumbered}  
#### phantomjs {.unnumbered}  
## RStudio {#rstudio}
### RStudio orientation {.unnumbered}  
### RStudio settings {.unnumbered}  
### Keyboard shortcuts {.unnumbered}  
## Functions {#functions}  
### Simple functions {.unnumbered}  
### Functions with multiple arguments {.unnumbered}  
### Writing Functions {.unnumbered}  
## Packages {#packages}  
### Install and load {.unnumbered}  
#### Your library {.unnumbered}  
#### Install from CRAN {.unnumbered}  
#### How to install and load {.unnumbered}  
### Code syntax {.unnumbered}  
### Function help {.unnumbered}  
### Update packages {.unnumbered}  
### Delete packages {.unnumbered}
### Dependencies {.unnumbered}  
### Masked functions {.unnumbered}  
### Detach / unload {.unnumbered}  
### Install older version {.unnumbered}  
### Suggested packages {.unnumbered}  
## Scripts {#scripts}
### Commenting {.unnumbered}  
### Style {.unnumbered}  
### Example Script {.unnumbered}  
### R markdown {.unnumbered}
### R notebooks {.unnumbered}
### Shiny {.unnumbered}
### Code folding {.unnumbered}  
## Working directory  
### Recommended approach {.unnumbered}  
### Set by command {.unnumbered}
### Set manually {.unnumbered}  
### Within an R project {.unnumbered}
### Working directory in an R markdown {.unnumbered}
### Providing file paths {.unnumbered}  
## Objects {#objects}
### Everything is an object {.unnumbered} 
### Defining objects (`<-`) {.unnumbered}
### Object structure {.unnumbered}  
### Object classes  {.unnumbered}
### Columns/Variables (`$`) {.unnumbered}  
### Access/index with brackets (`[ ]`) {.unnumbered}  
### Remove objects {.unnumbered} 
## Piping (`%>%`)  
### **Pipes** {.unnumbered}
### Define intermediate objects {.unnumbered}
## Key operators and functions {#operators}
### Assignment operators {.unnumbered}  
### Relational and logical operators {.unnumbered}  
### Missing values {.unnumbered}
### Mathematics and statistics {.unnumbered}  
#### Mathematical operators {.unnumbered} 
#### Mathematical functions {.unnumbered}
#### Scientific notation {.unnumbered}
#### Rounding {.unnumbered}  
#### Statistical functions {.unnumbered}  
#### Other useful functions {.unnumbered}  
### `%in%` {.unnumbered}  
## Errors & warnings  
### Error versus Warning {.unnumbered}
### General syntax tips {.unnumbered}
### Code assists {.unnumbered}  

<!--chapter:end:new_pages/basics.Rmd-->


# Transition to R { }  

Placeholder


## From Excel  
### Benefits {.unnumbered}  
### Tidy data {.unnumbered}  
### Functions {.unnumbered}  
### Scripts {.unnumbered}  
### Excel-to-R resources {.unnumbered}
### R-Excel interaction {.unnumbered}  
## From Stata  
## From SAS  
## Data interoperability  

<!--chapter:end:new_pages/transition_to_R.Rmd-->


# Санал болгох багцууд

Placeholder


## CRAN -ын багцууд  
## Github-ын багцууд  

<!--chapter:end:new_pages/packages_suggested.Rmd-->


# R төсөл {}  

Placeholder


## Санал болгож буй хэрэглээ
## R төсөл үүсгэх {}
### Төслүүдийг сэлгэх {.unnumbered}
### Тохируулга {.unnumbered}  
### Бүтэц {.unnumbered}  
### Хувилбаруудыг хянах {.unnumbered}  
## Жишээ  

<!--chapter:end:new_pages/r_projects.Rmd-->

# Импортлох ба экспортлох

<img src="/Users/bolor/Documents/GitHub/epiRhandbook_mn/images/Import_Export_1500x500.png" width="100%" />

Энэ бүлэгт бид файлыг хэрхэн байрлуулах, импортлох, экспортлох талаар тайлбарлав:

-   **rio** багцын `import()` болон `export()` --аар олон төрлийн файлуудыг чөлөөтэй импорт, экспорт хийх боломжтой

-   нэг компьютерт дэх файлын зам нөгөө компьютерт таарахгүй байх тохиолдолд **here** багцаар R төсөлтэй холбоотой файлуудын байршлыг тогтоох боломжтой. 

-   Дараахад файл зөөвөрлөлтийн төрлөөс дурьдав:

    -   Excel --ын хуудаснууд (sheets)

    -   Замбараагүй хүснэгтийн толгой, алдагдсан мөрнүүд

    -   Google sheets

    -   Вебсайтад тавигдсан өгөгдөл/дата

    -   API -ууд

    -   Хамгийн сүүлд хэрэглэж байсан файлыг оруулах

-   Гараар өгөгдлийг оруулах

-   R --т тусгай зориулагдсан файлын төрөл (RDS, RData)

-   Файл, графикуудыг хадгалж/экспортлох:

    -   

<!-- ======================================================= -->

## Ерөнхий

Аливаа "dataset" --ыг R--т оруулахад шинээр *data frame* гэсэн обьект таны R --ын орчинд үүсч байдаг. Энэ нь таны хавтсанд хаяг/байршилтай зөөвөрлөгдсөн (e.g. Excel, CSV, TSV, RDS) файл гэж үзэгддэг.

R--т олон төрлийн дата файл оруулж болдог ба бусад статистикийн программ (SAS, STATA, SPSS) дээр үүсгэсэн файлуудыг ч оруулах боломжтой. Мөн хамааралт өгөгдлийн санд ч холбох боломжтой (relational database).

R --дээрх дата өөрийн гэсэн өргөтгөлтэй

-   RDS файлд (.rds) ганц R обьектийг хадгалдаг (ж: datаframe). Ялангуяа цэвэрлэгдсэн өгөгдлийг хадгалахад тохиромжтой. Учир нь цэвэрлэгдсэн өгөгдөл багана тус бүр мэдээлэл хадгалагдсан учир. Энэ талаар [this section](https://epirhandbook.com/import-and-export.html#import_rds) --ээс тодруулж үзнэ үү.

-   RData файлд (.Rdata) хэд хэдэн обьект, эсвэл бүр бүтэн R-ын ажлын талбайг (workspace) хадгалахад хэрэглэж болно. Энэ талаар [this section](https://epirhandbook.com/import-and-export.html#import_rds) --ээс тодруулж үзнэ үү.

<!-- ======================================================= -->

## **rio** багц

Бидний санал болгож буй багц бол **rio. Энэхүү багцын нэр** "R I/O" (оролт/гаралт input/output) гэсэн үгний товчлол юм.

Энэ багцын `import()` болон `export()`нь олон төрлийн (e.g. .xlsx, .csv, .rds, .tsv) файлуудтай ажиллах чадвартай. Энэ функцуудэд файлын байршлыг (өргөтгөлтэй нь хамт ) зааж өгөхөд rio багц тухайн файлын өргөтгөлийг уншаад шаардагдах тохируулгыг хийж файлыг зөөвлөгднө.  

**rio** --ыг багцгүйгээр эдгээр үйлдлийг хийхэд хэд хэдэн багц хамтран оролцох
шаардлагатай болдог. Багц болгон тус тус өөр өргөтгөлийг уншихад зориулагдсан байдаг.  Тухайлбал `read.csv()` (**base** R), `read.xlsx()` (**openxlsx** багц), болон `write_csv()` (**readr** багц) гэх мэт функцуудыг ашиглах болдог. Эдгээрийг тэр болгон санахад бэрхшээлтэй тул **rio** багцын `import()` болон `export()` --ыг хэрэглэх нь илүү хялбар.

**rio** -ын `import()` болон `export()`--функцууд тухайн файлын өргөтгөлд шаардлагатай багцыг тогтоож хэрэглэдэг. rio  багц-ын функцуудыг уншуулж байхад цаана нь ажиллаж байдаг багцуудын жагсаалттай хүснэгт энэ бүлгийн хамгийн ард хүснэгтээр харуулсан. Rio багцаар зөөвөрлөгддөг файлуудын дунд STATA, SAS, SPSS программын файлууд ч ордог.

Харин shapefiles --г зөөвөрлөхөд өөр багц шаардлагатай байдаг. [GIS basics](https://epirhandbook.com/gis-basics.html#gis-basics) гэсэн хэсгээс
тодруулж уншина.

## **here** багц {#here}

**here** багц болон үүний `here()` функц  R --т таныг файлаа хаанаас олох болон хаана хадгалах талаар ойлгуулахыг хялбарчилж өгдөг. Өөрөөр хэлбэл файлын байршил үүсгэдэг. 

Мөн энэ here багц таны R төсөлдэх файлын байршлыг R  төслийн *үндсэн
лавлахтай* (хамгийн дээд түвшний хавтас) холбоотойгоор харуулдгаараа онцлог. R төслийг олон компьетер/хүмүүсийн дунд дамжуулж, ажиллаж буй үед энэхүү үйлдэл их хэрэг болдог. Нэг компьютер дээрх үүсгэгдсэн файлын байршил өөр нэг компьютерт очоод таарахгүй байх асуудал нийтлэг гардаг ба here багц үүнээс сэргийлж өгдөг. (`"C:/Users/Laura/Documents..."` гэх мэтээр бүх хэрэглэгчдэд нийтлэг байршлаар эхэдэг (R төслийн үндсэн байршил).

`here()` нь R төсөлд дараах зарчмаар ажилладаг.

-   Анх here багцыг ачааллах үед R төслийн үндсэн хавтас дотор  ".here" гэсэн жижиг файл автоматаар үүсгэгдэж "чиглүүлэх"/холбох үүрэг гүйцэтгэдэг.

-   Код бичиж байхдаа аливаа файлын байршлыг заах бол `here()` -- ашигласнаар дээрх чиглүүлэгч үүсгэсэн холбоостой холбогдно.

-   Файлын байршлыг үүсгэхдээ оруулах хавтасны нэр (үндсэн хавтаснаас цааш)-ийг тодорхойлох цэгтэйгээх, таслалаар тусгаарлаж, файлын нэрийг өргөтгөлтэй нь хамт бичнэ. Доор жишээ харуулав.

-   `here()` file-ыг файл зөөж оруулах,гаргах аль алинд нь ашиглаж болно.

    Жишээ нь дараах `import()` функцдэх файлын байршлыг  `here()` --ийг ашиглан оруулсан байна.


```r
linelist <- import(here("data", "linelists", "ebola_linelist.xlsx"))
```

`here("data", "linelists", "ebola_linelist.xlsx")` коммандаар зөвхөн хэрэглэгчийн компьютерт л өвөрмөц файлын байршлыг үүсгэсэн байна.

    "C:/Users/Laura/Documents/my_R_project/data/linelists/ebola_linelist.xlsx"

`here()`  багцын хамгийн давуу тал нь ямар ч компьютер байсан тухайн R төсөлд хүрч чаддагт байдаг. can be successfully run on any computer accessing the R project.

***ЗӨВЛӨГӨӨ:*** ".here" яг хаана үүсч байгааг мэдэхийг хүсвэл, `here()` функцыг хоосон хаалттайгаар уншуулаад үзнэ үү.

[***TIP:*** If you are unsure where the ".here" root is set to, run the function `here()` with empty parentheses.]{style="color: darkgreen;"}

**here** багцын талаар [at this link](https://here.r-lib.org/)-ээс уншна уу.

<!-- ======================================================= -->

## Файлын зам

Өгөгдлийг зөөж оруулж гаргахдаа байршлыг нь зааж өгөх хэрэгтэй байдаг. Үүнийг дараах гурван аргаар хийж болно:

1.  *Санал болгож буй арга:* **here** багцыг ашиглаж файлыгн " холбоотой (relative)" замыг заана.

2.  файлын "бүтэн" буюу "жинхэнэ (absolute)" замыг зааж өгнө.

3.  Гар аргаар (manuel) файлыг сонгож болно

### Файлын "холбоотой" зам {.unnumbered}

"Холбоотой (relative)" зам гэдэг нь файлын зам R-төслийн үндсэн хавтастай *холбоотой* байхыг хэлнэ. Ингэснээр өөр компьютер дээр ажиллах үед файлын байршлыг тогтооход маш хялбар болдог ( R төслийг тухайлбал email --ээр илгээх, эсвэл дундын драйв дээр зэрэг үед). Дээр дурьдсанчлан "холбоотой (relative)" замыг тогтоохдоо **here** багцыг ашиглана.

`here()`  --ийг ашиглаж файлын харьцангүй байршлыг олох жишээг доор харуулав. Жишээнд R төслийн үндсэн хавтаст "дата" гэсэн хавтас байх ба энэ хавтаст дахиад салбар хавтас болох "linelists" гэсэн хавтас байгаа ба үүн дотор бидний ажиллах .xlsx өргөтгөлтэй файл байгаа гэж үзсэн.

    linelist <- import(here("data", "linelists", "ebola_linelist.xlsx"))


```r
linelist <- import(here("data", "linelists", "ebola_linelist.xlsx"))
```

### Файлын "жинхэнэ" зам {.unnumbered}

Файлын "жинхэнэ" замыг [import()](https://rdrr.io/pkg/rio/man/import.html) гэх мэт функцэд оруулж өгөхийг хэлнэ. Гэвч энэ нь зөвхөн тухайн ажиллаж буй компьютерт л өвөрмөц байдаг тул амархан холбоос нь тасардаг тул тэр болгон *хэрэглэхгүй* байхыг зөвлөж байна.

Файлын үнэмлэхүй байршлын жишээг доор харуулав. Энд Лаурагийн компьютерт "analysis" дэд хавтас байгаа ба үүнд доторх "data" дэд хавтас дотор "linelists" гэсэн дэд хавтас байна. Үүний дотор бидний ажиллаж буй .xlsx өргөтгөлтэй файл байрлаж буй.


```r
linelist <- import("C:/Users/Laura/Documents/analysis/data/linelists/ebola_linelist.xlsx")
```

Үнэмлэхүй байршлыг ашиглахад анхаарах зүйлс:

-   **Өөр хүний компьютер дээр ажиллах үед файлын байршлын холбоос эвдэрдэг тул аль болох үнэмлэхүй байршил хэрэглэхээс зайлсхий.**

-   Урагшаа чиглэлтэй ташуу зураасыг ашигла (энэ нь ердийн Windows-ын үеийнхээс ӨӨР болохыг анхаар)

-   Давхар ташуу зураасаар эхэлдэг файлын байршлууд R программ танигдахгүй байх өндөр магадлалтай ба алдаа заадаг. Ажлаа "нэртэй" эсвэл "J:",  "C:" гэх мэт үсгээр дугаарласан дискэнд хадгалахыг зөвлөж байна. Энэ талаар  [Directory interactions](https://epirhandbook.com/directory-interactions.html#directory-interactions) хэсгээс нэмж тодруулж болно.

Дундын драйв дээрх файлын байршил тэр файлыг хэрэглэж буй бүх хүний компьютерт адилхан байхаар бичигдсэн үед үнэмлэхүй байршлыг ашиглах нь зөв.

***ЗӨВЛӨГӨӨ:***  `\` тэмдэгтийг [/](https://rdrr.io/r/base/Arithmetic.html) -ээр түргэн солихыг тулд Ctrl+f ( Windows-г) дарж гарах цэснээс "In selection"-г сонго. Үүний дараа тэмдэгт солих үйлдэл хийж нэг дор солих боломжтой.  

[***TIP:*** To quickly convert all `\` to `/`, highlight the code of interest, use Ctrl+f (in Windows), check the option box for "In selection", and then use the replace functionality to convert them.]{style="color: darkgreen;"}

<!-- ======================================================= -->

### Гар аргаар байршлыг сонгох
 {.unnumbered}

Дараах аргуудыг хэрэглэж мануэль сонголт хийнэ:

1.  RStudio --ын Орчин (Environment) цонхны "Import Dataset"-г дарж гарах цэснээс өгөгдлийн төрлийг сонгоно.

2.  File / Import Dataset --г дарж өгөгдлийн төрлийг сонгоно

3.  Хамгийн их мануэль гэж үзэгддэг арга бол *base R --ын file.choose() --ыг хоосон хаалттайгаар  уншуулж* **pop-up цонхыг гаргаж ирж файлаа өөрөө сонгох юм.** Тухайлбал:


```r
# Файлыг мануэлэр сонгох. Дараах коммандыг уншуулахад POP-UP цонх нээгднэ. 
# Сонгосон файлын байршил import() коммандын дотор бичигдэх болно.

my_data <- import(file.choose())
```

***ЗӨВЛӨГӨӨ:***  **pop-up цонх**  RStudio цонхны АРД нээгдсэн байж болохыг анхаар.

[***TIP:*** The **pop-up window** may appear BEHIND your RStudio window.]{style="color: darkgreen;"}

## Дата импортлох

[import()](https://rdrr.io/pkg/rio/man/import.html) -г ашиглан өгөгдлийг зөөвөрлөх нь харьцангуй энгийн. Хаалтан дотор файлын байршлыг (файлын нэр өргөтгэлтэй нь хамт) хашилттай бичихэд болно. Хэрэв [here()](https://here.r-lib.org/reference/here.html) t-г ашиглан файлын байршлыг тодорхойлох бол өмнө дурьдсан жишээг хар. Жишээ кодууд:

"ажлын хавтаст" эсвэл R --ын үндсэн хавтаст байрлах csv өргөтгөлтэй файлыг оруулах:


```r
linelist <- import("linelist_cleaned.csv")
```

R төсөлдэх "data" хавтсын  "linelists"дэд хавтсан дах Excel --файлын эхний sheet --ийг оруулах ([here()](https://here.r-lib.org/reference/here.html)-г ашиглаж буй үед):


```r
linelist <- import(here("data", "linelists", "linelist_cleaned.xlsx"))
```

Файлын үнэмлэхүй байршлыг дуудаж өгөгдлийг (жишээ нь .rds файл) оруулах:


```r
linelist <- import("C:/Users/Laura/Documents/tuberculosis/data/linelists/linelist_cleaned.rds")
```

### Excel-ийн sheet- тэй ажиллах

Excel (.xlsx) файлыг [import()](https://rdrr.io/pkg/rio/man/import.html)-д дуудаж оруулахад эхний sheet автоматаар зөөвөрлөгдөж ордог. Хэрэв тодорхой sheet --ийг дуудаж оруулах бол  [import()](https://rdrr.io/pkg/rio/man/import.html) функцийн which аргументэд sheet-ийн нэрийг бичиж өгнө. Жишээ нь:


```r
my_data <- import("my_excel_file.xlsx", which = "Sheetname")
```

[here()](https://here.r-lib.org/reference/here.html) аргыг хэрэглэн харьцангуй байршлыг [import()](https://rdrr.io/pkg/rio/man/import.html)дотор уншуулах бол [here()](https://here.r-lib.org/reference/here.html) --ийн хаалт хаагдсаны дараа`which =`аргументэдийг нэмж sheet --ийнхээ нэрийг зааж өгч болно.


```r
# Demonstration: importing a specific Excel sheet when using relative pathways with the 'here' package
linelist_raw <- import(here("data", "linelist.xlsx"), which = "Sheet1")`  
```

R --аас өгөгдэлтэй хүснэгтийг Excel бусад sheet-ийн үүдэд нь өөрчлөлт оруулалгүйгээр зөвхөн тодорхой нэг sheet-руу экспортлонгоо бол **openxlsx** зэрэг тусгай багц ашиглан зөөж, өөрчилж болно. Энэ талаар [Directory interactions](https://epirhandbook.com/directory-interactions.html#directory-interactions) or [at this github page](https://ycphs.github.io/openxlsx/) хэсгээс хар.

Та Excel-ийн .xlsb (binary хэлбэлтэй Excel файл) **rio**-г ашиглан зөөвөрлөх боломжгүй. Ийм тохиолдолд.xlsx болгож дахин хадгалаж болно. Эсвэл ийм тохиолдолд зориулсан **readxlsb** багцыг ашиглаж болно.

<!-- ======================================================= -->

### Дутуу утга {#import_missing .unnumbered}

Өгөгдөл доторх дутуу утгуудыг зааж өгөх шаардлага гарч болно. R нь дутуу утгыг `NA` гэж бичдэг ([Missing data](https://epirhandbook.com/missing-data.html#missing-data) гэсэн хэсэгт заасанчлан) боловч таны өгөгдөл дотор дутуу утгыг 99 --ийн тоо, "Дутуу" гэх зэргээр тэмдэглэж эсвэл хоосон орхисон байж болох юм.

Энэ үед  [import()](https://rdrr.io/pkg/rio/man/import.html) дотор `na =` аргументийг ашиглан өөрийн өгөгдөлдэх дутуу утгыг хашилтад хийж (тоогоор тэмдэглэсэн байсан ч гэсэн) оруулна. Хэд хэдэн утгуудыг [c()](https://rdrr.io/r/base/c.html) функц ашиглан вектор хэлбэрээр оруулах бас боломжтой. Жишээ дор харуулав.

Энэ жишээнд зөөж оруулах өгөгдөлд "99" --ийг дутуу утгаар тэмдэглэсэн байсан ба R -д оруулахдаа `NA`  -руу хувиргаж байна.


```r
linelist <- import(here("data", "my_linelist.xlsx"), na = "99")
```

Энэ жишээнд оруулах өгөгдөлд "Дутуу", хоосон нүд, эсвэл " "(нэг зай) гэж бичигдсэн бүх утгуудыг R-т  `NA` болгож хувиргаж байна.


```r
linelist <- import(here("data", "my_linelist.csv"), na = c("Missing", "", " "))
```

<!-- ======================================================= -->

### Мөр алгасах {.unnumbered}

Зарим тохиолдолд зарим мөрийг оруулалгүйгээр өгөгдлийг зөөж оруулах хэрэг гардаг. Энэ тохиолдолд **rio** багцын [import()](https://rdrr.io/pkg/rio/man/import.html) функцийн `skip =` аргументийг ашиглаж болно (.xlsx зэрэг .csv файлтай ажиллаж буй үед). Алгасах мөрүүдийнхээ дугаарыг зааж өгнө.


```r
linelist_raw <- import("linelist_raw.xlsx", skip = 1)  # толгой (header) мөрийг оруулалгүйгээр өгөгдлийг оруулна.
```

`skip =` -ийн нэг дутагдалтай тал нь зөвхөн 1 бүхэл тоон утга л авдаг ба хэд хэдэн тоог оруулах боломжгүй  (жишээ нь "2:10" гэж бичвэл ажиллахгүй). Хэрэв дараалласан биш энд тэнд байгаа мөрнүүдийг алгасах хэрэгтэй бол **dplyr** багцын `bind_rows()` --ыг ашиглан олон дахин зөөж оруулж байж гүйцэтгэх боломжтой. Доор жишээнд ердөө 2 мөрийг алгасах байдлыг харуулав.

### Хоёрдах толгой (header) мөртэй ажиллах

Зарим тохиолдолд таны өгөгдлийн толгой 2 мөрнөөс бүтсэн байх боломжтой. Жишээ нь өгөгдлийн "нэрсийн тайлбар" --ийг хоёрдахь нүдэнд оруулсан байж болно. Үүнээс болоод багана болгон "character" хэлбэрээр орох аюултай.



Доор яг ийм өгөгдөлтэй хүснэгтийн жишээг харуулав (эхний багана нь баганын нэрсийн тайлбар).


```{=html}
<div id="htmlwidget-09d30c613809c4dfce9c" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-09d30c613809c4dfce9c">{"x":{"filter":"top","filterHTML":"<tr>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["case identification number assigned by MOH","5fe599","8689b7","11f8ea","b8812a"],["transmission chain generation number","4","4","2","3"],["estimated date of infection, mm/dd/yyyy","2014-05-08",null,null,"2014-05-04"],["date of symptom onset, YYYY-MM-DD","2014-05-13","2014-05-13","2014-05-16","2014-05-18"],["date of initial hospitalization, mm/dd/yyyy","2014-05-15","2014-05-14","2014-05-18","2014-05-20"],["date of outcome status determination",null,"2014-05-18","2014-05-30",null],["either 'Death' or 'Recovered' or 'Unknown'",null,"Recover","Recover",null],["either 'm' or 'f' or 'unknown'","m","f","m","f"],["age number","2","3","56","18"],["age unit, either 'years' or 'months' or 'days'","years","years","years","years"],[null,"2","3","56","18"],[null,"0-4","0-4","50-69","15-19"],[null,"0-4","0-4","55-59","15-19"],["Name of hospital of first admission","Other","Missing","St. Mark's Maternity Hospital (SMMH)","Port Hospital"],["longitude of residence, approx","-13.2157351064963","-13.2152339775486","-13.212910703914","-13.2363711169728"],["latitude of residence, approx","8.46897295100924","8.45171855856465","8.46481700596819","8.4754761613651"],["case_id of infector","f547d6",null,null,"f90f5f"],["context of known transmission event","other",null,null,"other"],[null,"27","25","91","41"],[null,"48","59","238","135"],[null,"22","22","21","23"],["presence of fever on admission, either 'yes' or 'no'","no",null,null,"no"],["presence of chills on admission, either 'yes' or 'no'","no",null,null,"no"],["presence of cough on admission, either 'yes' or 'no'","yes",null,null,"no"],["presence of aches on admission, either 'yes' or 'no'","no",null,null,"no"],["presence of vomiting on admission, either 'yes' or 'no'","yes",null,null,"no"],[null,"36.8","36.9","36.9","36.8"],["time of hospital admission HH:MM",null,"09:36","16:48","11:22"],[null,"117.1875","71.8184429761563","16.0652496292635","22.4965706447188"],[null,"2","1","2","2"]],"container":"<table class=\"white-space: nowrap\">\n  <thead>\n    <tr>\n      <th>case_id<\/th>\n      <th>generation<\/th>\n      <th>date_infection<\/th>\n      <th>date_onset<\/th>\n      <th>date_hospitalisation<\/th>\n      <th>date_outcome<\/th>\n      <th>outcome<\/th>\n      <th>gender<\/th>\n      <th>age<\/th>\n      <th>age_unit<\/th>\n      <th>age_years<\/th>\n      <th>age_cat<\/th>\n      <th>age_cat5<\/th>\n      <th>hospital<\/th>\n      <th>lon<\/th>\n      <th>lat<\/th>\n      <th>infector<\/th>\n      <th>source<\/th>\n      <th>wt_kg<\/th>\n      <th>ht_cm<\/th>\n      <th>ct_blood<\/th>\n      <th>fever<\/th>\n      <th>chills<\/th>\n      <th>cough<\/th>\n      <th>aches<\/th>\n      <th>vomit<\/th>\n      <th>temp<\/th>\n      <th>time_admission<\/th>\n      <th>bmi<\/th>\n      <th>days_onset_hosp<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"pageLength":4,"scrollX":true,"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true,"lengthMenu":[4,10,25,50,100]}},"evals":[],"jsHooks":[]}</script>
```

#### Хоёрдах толгой мөрийг арилгах

Хоёр дах мөрийг арилгахдаа, өгөгдлийг хоёр удаа зөөж оруулах болно.

1.  Эхлээд өгөгдлийг зөөж оруулснаар баганын зөв нэрсийг хадгалагдна.

2.  Өгөгдлийг дахин оруулахдаа, эхний 2 мөрийг (толгой болон 2 дахь мөр )алгас гэж комманд өгнө.

3.  Эхний хоёр мөр алгассан хүснэгтэд өмнө нь оруулсан нэрсээ тохирох баганад нь холбож өгнө.

Баганын нэрсийг зөв баганад нь холбох үйлдэл өгөгдлийн төрлөөс хамаарч өөр байна ( жишээ нь .csv, .tsv, .xlsx,). Учир нь rio багц файлын төрлөөс хамаарч өөр функц ашигладаг. Үүнийг доорх хүснэгтэд харуулав.

**Excel файл бол:** (`col_names =`)


```r
# Эхлээд нэрсийг зөөж оруул; баганыг хадгал.
linelist_raw_names <- import("linelist_raw.xlsx") %>% names()  # баганын жинхэнэ нэрийг хадгалах


# өгөгдлийг дахин зөөж оруул; эхний 2 мөрийг алгасаад col_names = аргументэд өмнө нь хадгалсан нэрсийг зааж, баганын толгойг нэртэй болгоно
linelist_raw <- import("linelist_raw.xlsx",
                       skip = 2,
                       col_names = linelist_raw_names
                       ) 
```

**CSV бол:** (`col.names =`)


```r
# Эхлээд нэрсийг зөөж оруул; баганыг хадгал.
linelist_raw_names <- import("linelist_raw.csv") %>% names() #баганын жинхэнэ нэрийг хадгалах

# csv файлын баганын нэр асуусан аргумент нь өөр буюу 'col.names = '  гэж бичигдсэнийг анхаар 
linelist_raw <- import("linelist_raw.csv",
                       skip = 2,
                       col.names = linelist_raw_names
                       ) 
```

**Нэмэлт хувилбар :** баганын нэрийг өөрчлөхдөө тусдаа комманд ашиглаж болно


```r
# хүснэгтийн толгойг R base –ийн 'colnames()' –ийг ашиглан дахин бич.
colnames(linelist_raw) <- linelist_raw_names
```

#### Нэрсийн тайлбар толь (data dictionary) үүсгэх {.unnumbered}

Бонус! нэрсийн тайлбар хоёрдах бичигдсэн хүснэгтийн хоёрдах мөрийг ашиглан та өөртөө жинхэнэ нэрсийн тайлбар бий болгох боломжтой. Энэ санааг [post](https://alison.rbind.io/post/2018-02-23-read-multiple-header-rows/) зааварт тайлбарласан байсан.


```r
dict <- linelist_2headers %>%             # эхлэл: эхний мөр нь нэрсийн тайлбар байна 
  head(1) %>%                             # зөвхөн баганын нэрс болон нэрсийн тайлбарыг авч үлд
  pivot_longer(cols = everything(),       # бүх баганыг эргүүлж урт хэлбэрт шилжүүл
               names_to = "Column",       # шинэ үүссэн багануудыг нэрлэ
               values_to = "Description")
```


```{=html}
<div id="htmlwidget-22e352640f0cd5015518" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-22e352640f0cd5015518">{"x":{"filter":"top","filterHTML":"<tr>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["case_id","generation","date_infection","date_onset","date_hospitalisation","date_outcome","outcome","gender","age","age_unit","age_years","age_cat","age_cat5","hospital","lon","lat","infector","source","wt_kg","ht_cm","ct_blood","fever","chills","cough","aches","vomit","temp","time_admission","bmi","days_onset_hosp"],["case identification number assigned by MOH","transmission chain generation number","estimated date of infection, mm/dd/yyyy","date of symptom onset, YYYY-MM-DD","date of initial hospitalization, mm/dd/yyyy","date of outcome status determination","either 'Death' or 'Recovered' or 'Unknown'","either 'm' or 'f' or 'unknown'","age number","age unit, either 'years' or 'months' or 'days'",null,null,null,"Name of hospital of first admission","longitude of residence, approx","latitude of residence, approx","case_id of infector","context of known transmission event",null,null,null,"presence of fever on admission, either 'yes' or 'no'","presence of chills on admission, either 'yes' or 'no'","presence of cough on admission, either 'yes' or 'no'","presence of aches on admission, either 'yes' or 'no'","presence of vomiting on admission, either 'yes' or 'no'",null,"time of hospital admission HH:MM",null,null]],"container":"<table class=\"white-space: nowrap\">\n  <thead>\n    <tr>\n      <th>Column<\/th>\n      <th>Description<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"pageLength":4,"scrollX":true,"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true,"lengthMenu":[4,10,25,50,100]}},"evals":[],"jsHooks":[]}</script>
```

#### Хоёр толгой мөрийг нэгтгэх

Таны боловсруулагдаагүй байгаа хүснэгт хоёр толгой мөртэй байж болно (тухайлбал хоёрдах мөр нь баганын туслах гарчиг байж болно). Энэ үед нэтгэх буюу, хоёрдах мөрөндөх утгыг эхний мөрөндэх утгат нэмж оруулах шаардлага гарч магад.

Доорх кодоор баганын нэрийг анхны хүснэгтийн эхний мөр болон түүний доорх мөртэй хамт нэгтгэн оруулдаг. The command below will define the data frame's column names as the combination (pasting together) of the first (true) headers with the value immediately underneath (in the first row).


```r
names(my_data) <- paste(names(my_data), my_data[1, ], sep = "_")
```

<!-- ======================================================= -->

### Google --ийн хүснэгт

Сүлжээнд ажиллуулдаг google --ийн хүснэгтийн хуудсыг зөөж оруулах бол **googlesheet4 багцыг ашиглаад, google-руу орох хандалтаа баталгаажуулна оруулж болно.**  


```r
pacman::p_load("googlesheets4")
```

Доор google --ийн хүснэгтийн хуудсыг оруулах жишээг харуулав.  Энэ коммандыг ажиллуудахад таныг google account --аа баталгаажуулахыг шаардаж магадгүй юм. Энэ үед интернетийн браузер дээр гарч ирсэн цонх, pop-up уудад зөвшөөрөл олгосноор Tidyverse API- багцууд таны google drive дээрх хүснэгтийг засаж, арилгах шинээр үүсгэх зөвшөөрлийг авах юм.

Доорх хүснэгт нь "линкээр орсон хүн болгон үзэх боломжтой" ("viewable for anyone with the link") гэсэн тохируулгатай учир та энэ линкийг ашиглаж зөөж оруулж болно.


```r
Gsheets_demo <- read_sheet("https://docs.google.com/spreadsheets/d/1scgtzkVLLHAe5a6_eFQEwkZcc14yFUx1KgOMZ4AKUfY/edit#gid=0")
```

Энэ хүснэгтийг зөвхөн тухайн хүснэгтийн ID--г ашиглан оруулж болох ба URL-ын товчилсон хэлбэр нь:


```r
Gsheets_demo <- read_sheet("1scgtzkVLLHAe5a6_eFQEwkZcc14yFUx1KgOMZ4AKUfY")
```

Мөн ижил үйлдлийг хийдэг өөр нэгэн багц бол **googledrive. Үүнийг ашиглаж google хүснэгтийг янзалж, арилгаж, шинээр үүсгэх болдог. Энэ багцад** жишээ нь `gs4_create()` , `sheet_write()` гэх мэт функцууд ордог.

Доорх линкүүдэд дэлгэрүүлж заасан хичээлүүд буй: \
[basic Google sheets importing tutorial](https://arbor-analytics.com/post/getting-your-data-into-r-from-google-sheets/)\
[more detailed tutorial](https://googlesheets4.tidyverse.org/articles/googlesheets4.html)\
[interaction between the googlesheets4 and tidyverse](https://googlesheets4.tidyverse.org/articles/articles/drive-and-sheets.html)

## Олон файлтай зэрэг ажиллах - импорт, экспорт, хуваах, нэгтгэх

Олон файлуудыг импортлох, нэгтгэх, эсвэл олон Эксэл файлтай зэрэг ажиллах жишээг [Iteration, loops, and lists](https://epirhandbook.com/iteration-loops-and-lists.html#iteration-loops-and-lists)  хэсгээс харж болно. Хүснэгтийг хэрхэн хуваах, хуваасан хэсэг тус бүрийг экспортлох, болон Экселийн тусгай sheet болгон хадгалах зэрэг жишээг энэ линкээс харж болно.

<!-- ======================================================= -->

## Github-аас импорт хийх {#import_github}

Github аас R руу өгөгдөл оруулах нь хялбар ба файлын төрлөөсөөө хамаарч цөөхөн үйлдэлтэй байж болно. Дараах аргуудыг хэрэглэнэ.

### CSV файл {.unnumbered}

Github-аас .csv файлыг R луу шууд R коммандаар хялбар оруулдаг.

1.  Github --ийн агуулахыг нээнэ, оруулах файлаа байрлуулаад дээр нь дар

2.   "Raw" товчийг дар ( "raw" csv гэсэн өгөгдлийг харах болно, доор харуулав)

3.  URL (вебхаяг )-г хуулбарла

4.  URL --г хашилттайгаар [import()](https://rdrr.io/pkg/rio/man/import.html) функцэд оруулж R коммандэд уншуул

<img src="/Users/bolor/Documents/GitHub/epiRhandbook_mn/images/download_csv_raw.png" width="100%" style="display: block; margin: auto auto auto 0;" />

### XLSX файл {.unnumbered}

Зарим файлны "Raw" өгөгдлийг харах боломжгүй байдал гардаг (.xlsx, .rds, .nwk, .shp гэх мэт).

1.  Github --ийн агуулахыг нээнэ, оруулах файлаа байрлуулаад дээр нь дар

2.   "Download" товчоор татаж аваад (доор зурагт харуулсан)

3.  Файлыг компьютертээ хадгалаад дараа нь R луу импорт хий.

<img src="/Users/bolor/Documents/GitHub/epiRhandbook_mn/images/download_xlsx.png" width="100%" style="display: block; margin: auto auto auto 0;" />

### Shapefiles {.unnumbered}

Shapefiles файл нь олон дэд бүрэлдэхүүн хэсгүүдтэй, хэсэг тус бүр өөр өргөтгөлтэй байдаг. Нэг файл ".shp" гэсэн өргөтгөлтэй байхад нөгөө файл ".dbf", ".prj" гэх мэт байдаг. Github-аас shapefile татахад дэд бүрэлдэхүүүн бүрийг тусдаа татаж аваад өөрийн компьютертээ нэг хавтаст хийж хадгалах шаардлагатай байдаг. Github дээрх байгаа тусдаа файлууд дээр нэг нэгээр дарж "Download" товчийг дарж татаж авна.

 

Компьютерт хадгалагдсны дараа shapefile --аа **sf** багцын `st_read()` --г ашиглан
импорт хийнэ ( [GIS basics](https://epirhandbook.com/gis-basics.html#gis-basics) хэсэгт заасан буй). Та зөвхөн файлын зам болон ".shp"  файлынхаа нэрийг зааж өгөхөд л болно (тухайн ".shp файлтай холбоотой бусад файл нь ижил хавтаст байрлаж байх шаардлагатай).

Доорх жишээнд "sle_adm3" гэсэх олон файлаас бүрэлдсэн shapefile хэрхэн Github татагдах талаар харуулав.

<img src="/Users/bolor/Documents/GitHub/epiRhandbook_mn/images/download_shp.png" width="100%" style="display: block; margin: auto auto auto 0;" />

<!-- ======================================================= -->

## Гараар дата оруулах

### Мөр дагуу оруулах

tidyverse --д ордог багцуудын нэг **tibble багцын**`tribble`  функцийг ашигла ([online tibble
reference](https://tibble.tidyverse.org/reference/tribble.html)).

Баганын толгой *tilde* ([\~](https://rdrr.io/r/base/tilde.html)) тэмдэгтээр эхэлж буйг анхаар. Мөн багана болгон нэг л төрлийн өгөгдөл агуулсан байна (character, numeric гэх мэт.). Кодыг илүү уншихад амар байх зорилгоор багана болгоны араас таб, зай авах, шинэ мөр эхлэх зэргээр тохируулж бичиж болно. Утгуудын хоорондох зай авсан эсэх нь чухал биш, харин мөр болгоныг шинэ мөрнөөс эхэлж бичих хэрэгтэй. Жишээ нь:


```r
# Мөрийн дагуу өгөгдлийг оруулах
manual_entry_rows <- tibble::tribble(
  ~colA, ~colB,
  "a",   1,
  "b",   2,
  "c",   3
  )
```

Үүсгэсэн хүснэгт нь дараах байдлаар харагдна:


```{=html}
<div id="htmlwidget-f3b7e20a43713f715e8a" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-f3b7e20a43713f715e8a">{"x":{"filter":"none","data":[["1","2","3"],["a","b","c"],[1,2,3]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>colA<\/th>\n      <th>colB<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":2},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>
```

### Багана дагуу оруулах

Хүснэгт нь векторуудаас бүтдэг (вертикал багана).  Mануэль аргаар хүснэгт үүсгэх үед багануудаа эхлээд үүсгээд дараа нь нэгтгэдэг. Тархвар судлалын хувьд энэ нь эсрэгээрээ буюу өгөгдлийг ихэвчдлэн мөрийн дагуу эхэлж оруулдаг (дээрх жишээ).


```r
# define each vector (vertical column) separately, each with its own name
PatientID <- c(235, 452, 778, 111)
Treatment <- c("Yes", "No", "Yes", "Yes")
Death     <- c(1, 0, 1, 0)
```

[***CAUTION:*** All vectors must be the same length (same number of values).]{style="color: orange;"}

***Анхааруулга:*** Бүх векторууд нь ижил урттай (ижил тооны утгатай) байна.

Векторуудыг [data.frame()](https://rdrr.io/r/base/data.frame.html)функцыг ашиглаж нэгтгэдэг:


```r
# Багануудыг нэгтгэхдээ векторын нэрсийг оруулж нэтгэн хүснэгт үүсгэдэг
manual_entry_cols <- data.frame(PatientID, Treatment, Death)
```

Үүсгэсэн хүснэгт нь дараах байдлаар харагдна:


```{=html}
<div id="htmlwidget-b15b3414590789d283a8" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-b15b3414590789d283a8">{"x":{"filter":"none","data":[["1","2","3","4"],[235,452,778,111],["Yes","No","Yes","Yes"],[1,0,1,0]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>PatientID<\/th>\n      <th>Treatment<\/th>\n      <th>Death<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[1,3]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>
```

### Clipboard-оос хуулж авах

Хаа нэгтгээс өгөгдөл хуулж Clipboard -доо авсан бол дараах аргуудыг хэрэглэж болно.

**clipr** багцын use `read_clip_tbl()` --ыг ашиглан хүснэгт хэлбэрээр оруулна эсвэл `read_clip()` --ийг уншуулж character хэлбэрээр өгөгдлийг оруулж болно. Хаалтыг хоосон орхино.


```r
linelist <- clipr::read_clip_tbl()  # clipboard дахь өгөгдлийг хүснэгт хэлбэрээр оруул
linelist <- clipr::read_clip()      # character хэлбэрээр оруул
```

Системийн clipboard-д хуулагдсан бол **clipr-**ийг ашиглан амархан экспортолж болно. Экспорт хэсэгт дэлгэрүүлж бичсэн

Мөн **base** R-ын [read.table()](https://rdrr.io/r/utils/read.table.html) --г `file = "clipboard"` гэсэн аргументтэйгээр уншуулахад өгөгдөл хүснэгт хэлбэрээр орно:


```r
df_from_clipboard <- read.table(
  file = "clipboard",  # specify this as "clipboard"
  sep = "t",           # separator could be tab, or commas, etc.
  header=TRUE)         # if there is a header row
```

## Хамгийн сүүлд хэрэглэж байсан файлыг импортлох

Та өгөгдөлдөө өдөр бүр шинэчлэлт оруулдаг байж болох юм. Энэ тохиолдолд та хамгийн сүүлд хэрэглэж байсан файл гэж имплортолж болно. Үүнийг гүйцэтгэх хоёр янзын арга буй:

-   файлын нэрд бичигдсэн өдөр сарын дагуу файлыг сонгох

-   файлын метадатад бичигдсэн өдөр сарын дагуу файлыг сонгох (хамгийн сүүлд хийсэн өөрчлөлтийн он сар)

### Файлын нэр дээрх огноо

Үүнд дараах гурван нөхцөл бүрдсэн байна:

1.  Файлын нэр дээр бичигдсэн өдөр сард итгэх

2.  Он сарыг тоогоор бичсэн ба ерөнхийдөө ижил форматтай байна (жил, сар, өдөр гэх мэт)

3.  Файлын нэрт өөр тоогоор бичигдсэн зүйл байхгүй байна.

Бид энд алхам бүрийг тайлбарлаад эцэст нь нэтгэсэн байдлаар харуулна.

Эхлээд **base** R-ын  [dir()](https://rdrr.io/r/base/list.files.html) --г ашиглаж сонгосон хавтас доторх файлын зөвхөн авна. [Directory
interactions](https://epirhandbook.com/directory-interactions.html#directory-interactions) хэсгээс [dir()](https://rdrr.io/r/base/list.files.html) --ийн талаар хар. Энэ жишээнд сонгосон хавтас нь R төслийн хавтас дах "data"  хавтсын доторх "example" хавтсанд буй "linelistst" хавтас юм.


```r
linelist_filenames <- dir(here("data", "example", "linelists")) # Хавтасны нэрийг авна

linelist_filenames                                              # хэвлэ
```

```
## [1] "20201007linelist.csv"          "case_linelist_2020-10-02.csv" 
## [3] "case_linelist_2020-10-03.csv"  "case_linelist_2020-10-04.csv" 
## [5] "case_linelist_2020-10-05.csv"  "case_linelist_2020-10-08.xlsx"
## [7] "case_linelist20201006.csv"
```

Файлын нэрсийг вектор болгож авсны дараа он сар бичигдсэн хэсгийг салгаж авахын тулд **stringr** багцын `str_extract()` болон regular expression ашиглана. Энэ нь файлын нэр дэх тоогоор бичигдсэн хэсгийг салгаж авдаг (дунд нь орсон зураас, ташуу зураас зэрэгтэй нь хамт). **stringr багцын талаар дэлгэрүүлж** [strings болон characters] **уншиж болно.**


```r
linelist_dates_raw <- stringr::str_extract(linelist_filenames, "[0-9].*[0-9]") # тоо болон тооны дунд бичигдсэн тэмдэгтүүдийг салгаж авна.
linelist_dates_raw  # хэвлэ
```

```
## [1] "20201007"   "2020-10-02" "2020-10-03" "2020-10-04" "2020-10-05"
## [6] "2020-10-08" "20201006"
```

Файлын нэрт огноо бичигдсэн байдал ерөнхийдөө ижилхэн ба жилийг 4 цифрээр бичсэн гэж  (жишээ нь жил, сар, өдөр ) үзье. Ийм тохиолдолд **lubridate багц хувирах чадвар сайтай** функцууд байдаг (`ymd()`, `dmy()`, or `mdy()`) ба эдгээрийг ашиглан өгөгдлийг огноо хэлбэрт оруулж болно. Эдгээр функцуудэд зураас, ташуу зураас, хоосон зай зэрэг нь хамаагүй ба зөвхөн огнооны дэс дараалал л чухал. Энэ талаар [Working with dates](https://epirhandbook.com/working-with-dates.html#working-with-dates-1) хэсгээс нэмж үз.


```r
linelist_dates_clean <- lubridate::ymd(linelist_dates_raw)
linelist_dates_clean
```

```
## [1] "2020-10-07" "2020-10-02" "2020-10-03" "2020-10-04" "2020-10-05"
## [6] "2020-10-08" "2020-10-06"
```

Дэс дарааг нь индекслэж дугаарлахын тулд (1 дүгээр, 2 дугаар, 3 дугаар)**base** R
-ын [which.max()](https://rdrr.io/r/base/which.min.html)-г ашиглаж огнооны хамгийн ихийг нь тогтооно.

Хамгийн сүүлд хэрэглэсэн файл 6 дугаар файл гэж зөв дугаарлагдсан байна -"case_linelist_2020-10-08.xlsx"


```r
index_latest_file <- which.max(linelist_dates_clean)
index_latest_file
```

```
## [1] 6
```

Эдгээр коммандуудыг нэгтгэж доор харуулав. Энэ кодны сүүлийн мөрөнд `.` байгаа
ба үүнийг pipe бичиж буй үед тухайн үед бичигдэж буй обьектийг илэрхийлэхийн тулд ашигладаг. Энэ үед бичигдэж буй обьект ердөө 6 гэсэн тоо байна.  [dir()](https://rdrr.io/r/base/list.files.html) --ээр үүсгэгдсэн файлын нэрстэй векторуудын 6 дугаар элэментийг гаргаж авахын тулд давхар хаалтын дотор үүнийг оруулсан байна.


```r
# Багцуудыг ачааллах
pacman::p_load(
  tidyverse,         # өгөгдлийн менежмент
  stringr,           # strings/characters-тай ажиллах
  lubridate,         # огноотой ажиллах
  rio,               # импорт / экспорт
  here,              # файлын харьцангуй зам
  fs)                # файлын байрлалуудын харилцан уялдаа 

# сүүлийн хэрэглэсэн файлын нэрийг салгаж ав 
latest_file <- dir(here("data", "example", "linelists")) %>%  # "linelists" гэсэн дэд хавтаснаас авна          
  str_extract("[0-9].*[0-9]") %>%                  # огноог салгаж авна (тоогоор бичигдсэн)

  ymd() %>%                                        # тоон утгыг огноо болгох (жил-сар-өдөр форматтай гэж үзэхэд)

  which.max() %>%                                  # огнооны хамгийн их тоог индекслэнэ (өөрөөр хэлбэл хамгийн сүүлд хэрэглэсэн файлын дугаар)

  dir(here("data", "example", "linelists"))[[.]]              # хамгийн сүүлд хэрэглэсэн linelist-ийн файлын нэрийг харуулах


latest_file  # сүүлд хэрэглэсэн файлын нэрийг хэвдэ
```

```
## [1] "case_linelist_2020-10-08.xlsx"
```

Одоо энэхүү нэрээ  [here()](https://here.r-lib.org/reference/here.html) багцад оруулж файлын харьцангуй замыг тодруулж болно:


```r
here("data", "example", "linelists", latest_file) 
```

одоо хамгийн сүүлд хэрэглэж байсан файлыг импортолж болно:


```r
# import
import(here("data", "example", "linelists", latest_file)) # import 
```

### Файлын метадата ашиглах 

Хэрэв таны файлын нэр огноо агуулаагүй тохиолдолд (эсвэл та нэрэн дээрх огноонд илгэлгүй байгаа бол) тухайн файлын метадатанаас хамгйин сүүлд ашигласан огноог олж болно. Файлын метадатаг (сүүлд ашигласан огноо, файлын зам зэрэг) шалгахдаа **fs** багцын функцуудыг ашигладаг.

Дараах жишээнд сонгосон хавтсыг  **fs**-ын  `dir_info()` оруулж өгсөн. R төслийн хавтсан дах "data" хавтасны дэд хавтас болох "example" доторх "linelists" хавтсыг бид сонгосон. Ингэснээр файл тус бүрт нэг мөр үүсгэсэн,  мөн  `modification_time`, `path` зэрэг багануудтай хүснэгт бий болно. [Directory interactions](https://epirhandbook.com/directory-interactions.html#directory-interactions) --д жишээг илүү дэлгэрэнгүй харуулсан буй.

`Х`үснэгийн `modification_time` --г ашиглаж хүснэгтийг эрэмбэлэх боломжтой ба **base** R-ын [head()](https://rdrr.io/r/utils/head.html)функцээр зөвхөн эхний мөр буюу хамгийн сүүлд ашигласан файлтай мөрийг авч үлдэж болдог. Дараа нь dplyr багцын  `pull()` --функцыг `path` баганад хэрэглэж файлын замыг гаргаж авдаг. Эцэст нь энэ файлын замыг  [import()](https://rdrr.io/pkg/rio/man/import.html)-д оруулна. Импортлогдсон файлыг `latest_file`гэж хадгалсан.


```r
latest_file <- dir_info(here("data", "example", "linelists")) %>%  # тухайн байршил дахь бүх файлын талаарх метадатаг цуглуулах 

  arrange(desc(modification_time)) %>%      # өөрчлөлт оруулсан хугацаагаар нь эрэмблэ

  head(1) %>%                               # зөвхөн толгой мөрийг авч үлд
  pull(path) %>%                            # зөвхөн файлын замыг авч үлд
  import()                                  # файлыг импорт хий
```

<!-- ======================================================= -->

## APIs {#import_api}

Автомат Программын Интерфэйс (Automated Programming Interface) (API) --аар вебсайтаас шууд өгөгдлийг авах хүсэлт гаргадаг. API гэдэг нь нэг тодорхой  Үйлчлүүлэгч (та) "хүсэлтээ" илгээсний дүнд мэдээлэл агуулсан "хариуг" хүлээж авдаг. R дээр **httr**, **jsonlite** багцууд энэ үйлдлийг гүйцэтгэдэг.

API --г идэвхижүүлсэн вебхуудас бүр тус бүрийн онцлогтой дүрэм, журмыг танилцуулсан байдаг. Зарим вебхуудас нийтэд нийлттэй, хэн ч орж үзэж болохоор байдаг. Зарим тохиолдолд тухайлбал ID, нууц үг хэрэглэдэг платформуудын мэдээлэллийг авахын тулд баталгаажуулалт шаардагддаг.

API --аар мэдээлэл импортлоход мэдээж сүлжээнд холбогдсон байна. API ашиглан мэдээлэл импортлох богинохон жишээг харуулж, цаашид унших линкийг дор дурьдсан.

Анхааруулга: Өгөгдөл/мэдээлэл вебхуудаст ямар ч API гүйгээр тавигдсан байвал татаж авахад хялбар байх талтай. Жишээ нь CSV файлыг сайтын URL-г [import()](https://rdrr.io/pkg/rio/man/import.html) дотор оруулснаар ( [importing from Github](https://epirhandbook.com/import-and-export.html#import_github) хэсэгт заасанчлан ) шууд татаж авах боломжтой байж болно.

### HTTP request {.unnumbered}

API --ын солилцоог ихэвчлэн HTTP хүсэлт гаргаж гүйцэтгэдэг. HTTP гэдэг нь  Hypertext Transfer Protocol --ын товчлол бөгөөд энэ нь үйлчлүүлэгч, сервер хоёрын дундах хүсэлт/хариу солилцоход хэрэглэгддэг үндсэн формат юм.

API аас хамаарч нарийн өгөгдөл, гаргалт (input/output) нь өөр байж болох боловч үндсэн процесс нь адилхан. Энэ нь лавлагаа асуумж агуулсан хэрэглэгчээс ирж буй "Хүсэлт" ба хүсэлтийн статусыг заасан мэдээлэл болон хүсэлт гаргасан өгөгдөлтэй "Хариулт"-аас бүрддэг.  

*HTTP хүсэтлийн зарим бүрдэл хэсгүүд:*

-   API эцсийн цэгийн URL

-   "Аргачлал" (эсвэл "Үйл үг")

-   Толгой хэсэг

-   Бие хэсэг

HTTP хүсэлтийн "аргачлал" гэдэг нь таны үйлдэх гэж буй үйлдлийн нэр. Хамгийн элбэг хэрэглэгддэг хоёр HTTP аргачлалд `GET` болон `POST`. Бусад `PUT`, `DELETE`, `PATCH` зэрэг орно. R луу өгөгдөл импорт хийхэд ихэвчлэн `GET`-ийг хэрэглэнэ.

Хүсэлт гаргасны дараа таны компьютер хариуг хүлээж авна. Ирэх хариулт таны илгээсэн мэдээлэлтэй төстэй форматаар буцаж ирнэ. Үүнд URL, HTTP статус (Статусыг 200 байлгах нь чухал), файлын төрөл, хэмжээ болон гол авах гэсэн мэдээлэл, өгөгдөл зэрэг ирнэ. Та ирсэн мэдээллийг ялгаж, R --ын орчинруу хүснэгт хэлбэрээр оруулах шаардлагатай.

### Багцууд

R дээр HTTP хүсэлт гаргахад илүү хэрэглэгддэг багцыг **httr гэдэг. Үүнийг ашиглахад Веб API --ын талаарх бага зэргийн мэдлэг шаардагддаг ба компьютер программчлалын хэллэг сайн мэдэхгүй хүмүүс хэрэглэх боломжтой.** Мөн зарим тохиолдол HTTP хүсэлт .json хэл дээр байдаг ба энэ үед **jsonlite** --аар ирсэн хариу


```r
# багцуудыг ачааллах
pacman::p_load(httr, jsonlite, tidyverse)
```

### Олон нийтэд нээлттэй дата

Дараах жишээнд HTTP хүсэлт гаргахыг харуулав. Жишээг  [the Trafford Data
Lab](https://www.trafforddatalab.io/open_data_companion/#A_quick_introduction_to_APIs) линк дээрх хичээлээс хуулбарласан ба энд API --ын хичээл, дасгалууд олон бий.

Жишээ хувилбар:

Бид Их Британийн Траффорд хотын түргэн хоолны газруудын жагсаалтыг импортлох хэрэгтэй боллоо. Энэ өгөгдлийг Их Британийн хоолны ариун цэврийн үнэлгээний мэдээллийг боловсруулдаг Хоолны Стандартын Агентлагийн API-д нэвтэрснээр авч болох юм.

Бидний хүсэлт гаргах параметрууд:

-   HTTP үйл үг: GET

-   API --ийн эцсийн цэг URL: <http://api.ratings.food.gov.uk/Establishments>

-   Сонгосон параметрүүд: нэр, хаяг, уртраг, өргөрөг, бизнессийн төрлийн дугаар, үнэлгээний төрөл, зөвшөөрөл өгөгчийн дугаар

-   Толгой: "x-api-version", 2

-   Өгөгдлийн формат(s): JSON, XML

-   Тэмдэглэл: <http://api.ratings.food.gov.uk/help>

Код нь дараах маягаар бичигдсэн байна:


```r
# Хүсэлтээ бэлд
path <- "http://api.ratings.food.gov.uk/Establishments"
request <- GET(url = path,
             query = list(
               localAuthorityId = 188,
               BusinessTypeId = 7844,
               pageNumber = 1,
               pageSize = 5000),
             add_headers("x-api-version" = "2"))

# server –т гарах алдааг хянах  ("200" байвал сайн!)
request$status_code

# хүсэлтийг илгээж, хариуг үнэлж, хүснэгт болгон хувига
response <- content(request, as = "text", encoding = "UTF-8") %>%
  fromJSON(flatten = TRUE) %>%
  pluck("establishments") %>%
  as_tibble()
```

Одоо тамөр бүртээ түргэн хоолны газрыг жагсаасан `response` хүснэгтийг ашиглах, янзалж болохоор боллоо.

### Баталгаажуулалт шаардлагатай үед

Зарим API --д хандалтын хязгаарлалттай мэдээлэл агуулагддаг бөгөөд эдгээр API-руу нэвтрэхийн тулд та өөрийгөө мөн эсэхийг баталгаажуулах шаардлага гардаг. Энэ үед эхлээд хэрэглэгчийн нэр, нууц үг, код POST аргаар оруулах хэрэгтэй. Ингэснээр нэвтрэх эрх (token) авдаг. Үүнийг дараа хийгдэх GET аргаар хүсэлт явуулж хүссэн өгөгдлөө татаж авна.

*Доорх жишээнд Go.Data* хэмээх өвчний дэгдэлтийг судалдаг хэрэгслээс лавлагаа асуумжыг хэрхэн татаж авах талаар харуулав. *Go.Data*  нь веб хэрэглэгч болон утасны мэдээлэл цуглуулдаг аппликэйшн хоорондын харилцаанд API --ыг ашигладаг. *Go.Data* дэлхий даяар ашиглагддаг. Өвчний дэгдэлтийн мэдээлэл нь нууцлал шаарддаг тул та зөвхөн өөрийн дэгдэлтийн мэдээллийг л авах боломжтой ба улмаар та өөрийгөө мөн баталгаажуулах шаардлагатай болдог.

Дараах жишээнд **httr болон jsonlite --г ашиглан хэрхэн** *Go.Data* --ын API-тай харьцаж дэгдэлт үеийн хавьтагсдын өгөгдлийг импорт хийх явцаас харуулав.


```r
# баталгаажуулалт
url <- "https://godatasampleURL.int/"           # Go.Data –н зөв url
username <- "username"                          # Go.Data -ийн хэрэглэгчийн нэр 
password <- "password"                          # Go.Data –ын нууц үг
outbreak_id <- "xxxxxx-xxxx-xxxx-xxxx-xxxxxxx"  # Go.Data дахь дэгдэлтийн ID 


# Нэвтрэх эрх, тасалбар (token)
url_request <- paste0(url,"api/oauth/token?access_token=123") # үндсэн URL хүсэлтийг тодорхойл


# хүсэлтийг бэлд
response <- POST(
  url = url_request,  
  body = list(
    username = username,    # дээр хадгалсан хэрэглэгчийн нэр, нууц үгээ ашиглан орох эрхийг баталгаажуулна
                               
    password = password),                                       
    encode = "json")

# хүсэлтийг илгээж, ирсэн хариуг задал
content <-
  content(response, as = "text") %>%
  fromJSON(flatten = TRUE) %>%          # сүлжилдсэн JSON-г нэгтгэ
  glimpse()

# Хариултад ирсэн нэвтрэх эрх (token)-ийг хадгал
access_token <- content$access_token    # нэвтрэх эрх (token)-ийг хадгалснаар дараагийн API –ийн үйлдлүүд хийгдэх боломжтой болно

# Дэгдэлтийн хавьтлуудын өгөгдлийг импортлох
# нэвтрэх эрх (token)-ийг хэрэглэ
response_contacts <- GET(
  paste0(url,"api/outbreaks/",outbreak_id,"/contacts"),          # GET хүсэлт
  add_headers(
    Authorization = paste("Bearer", access_token, sep = " ")))

json_contacts <- content(response_contacts, as = "text")         # текстийг JSON луу хувирга

contacts <- as_tibble(fromJSON(json_contacts, flatten = TRUE))   # fJSON –г tibble (хүснэгт) -руу хувирга
```

[***CAUTION:*** If you are importing large amounts of data from an API requiring authentication, it may time-out. To avoid this, retrieve access_token again before each API GET request and try using filters or limits in the query. ]{style="color: orange;"}

***Анхааруулга:*** API --ийн зөвшөөрөл шаардлагатай вебсайтаас том хэмжээний өгөгдөл цуглуулж байх үед сайт завсарлага авч үйлдэл зогсох магадлалтай. Үүнээс сэргийлж API GET хүсэлт болгоны өмнө нэвтрэх эрхийг (access_token) --ыг эргүүлж аваад асуумжыг хязгаарлах эсвэл шүүлтүүр ашигла.

[***TIP:*** The `fromJSON()` function in the **jsonlite** package does not fully un-nest the first time it's executed, so you will likely still have list items in your resulting tibble. You will need to further un-nest for certain variables; depending on how nested your .json is. To view more info on this, view the documentation for the **jsonlite** package, such as the [`flatten()` function](https://rdrr.io/cran/jsonlite/man/flatten.html). ]{style="color: darkgreen;"}

Нэмэлт мэдээлэл, зааврыг [LoopBack Explorer](https://loopback.io/doc/en/lb4/index.html), [Contact Tracing](https://epirhandbook.com/contact-tracing-1.html#contact-tracing-1) хуудас эсвэл [Go.Data
Github repository](https://worldhealthorganization.github.io/godata/api-docs)  доторх API зөвлөгөөнүүдийг хар.

[here](https://httr.r-lib.org/articles/quickstart.html) линкээс httr багцын талаар унш

Энэхүү хэсгийг бичихэд [this tutorial](https://www.dataquest.io/blog/r-api-tutorial/) болон [this tutorial](https://medium.com/@traffordDataLab/querying-apis-in-r-39029b73d5f1) хичээлүүдээс мөн ашигласан.

<!-- ======================================================= -->

## Экспорт хийх

**rio багцын** [export()](https://rdrr.io/pkg/rio/man/export.html) функцыг [import()](https://rdrr.io/pkg/rio/man/import.html) шиг хэрэглэдэг. Эхлээд хадгалах гэж буй R обьектоо оруулаад, хадгалах файлын замыг шинээр үүсгэж буй файлын нэр, өргөтгөлтэй хамт хашилттайгаар оруулна. Жишээ:

Доорх жишээгээр `linelist`гэсэн хүснэгтийг Excel  хүснэгт болгож R-ийн үндсэн ажлын хавтаст хадгалахыг харуулсан:


```r
export(linelist, "my_linelist.xlsx") # will save to working directory
```

Дээрх `linelist`хүснэгтийг csv файл болгож хадгалахад дээрх кодны өргөтгөлийг өөрчлөхөд болно. Үүнийгээ мөн [here()](https://here.r-lib.org/reference/here.html) багцаар файлын замыг тодорхойлж хадгалж болно.


```r
export(linelist, here("data", "clean", "my_linelist.csv"))
```

### clipboard-д экспорт хийх

Хүснэгтийг компьютерийнхээ "clipboard" --д экспорт хийхэд (дараагаар нь Excel, Google Spreadsheets зэрэг программуудад хуулбарлаж тавих зорилготой) **clipr багцын** `write_clip()` функцыг ашиглана.


```r
# export the linelist data frame to your system's clipboard
clipr::write_clip(linelist)
```

## RDS файлууд {#import_rds}

Хүснэгтийг .csv, .xlsx зэрэг өртгөтгөлөөс гадна .rds файлаар экспортлож болно. Энэ өргөтгөл нь зөвхөн R --т өвөрмөц хэрэглэгддэг ба тухайн өгөгдлийг R дээр дахин хэрэглэх гэж байгаа үед .rds хадгалвал тохиромжтой байдаг.

Багана тус бүрийн ямар төрлийн өгөгдөл агуулж байгаа талаар хадгалагдсан байдаг тул импорт хийхэд дахин янзалж,цэвэрлэх шаардлагагүй (Excel эсвэл CSV файлууд дээр энэ үйлдэл нь толгойны өвчин гэсэн үг !). Мөн файлын хэмжээ багасгадаг учир том хэмжээний өгөгдөл импорт, экспорт хийж буй үед ашиглахад тохиромжтой.

Жишээ нь та тархвар судлалын багтай ажиллаж байлаа гэж бодьё. Тэдний ГИС (GIS)-ийн багт файлууд явуулж газрын зураглал гаргах гэсэн бол .rds  файл явуулахад л болно (тэд бас R хэрэглэдэг бол)! Учир нь багана тус бүр дэх өгөгдлийн төрөл, шинж хэвээр хадгалагдсан байх тул тэдний хийх ажил хөнгөлж өгдөг.


```r
export(linelist, here("data", "clean", "my_linelist.rds"))
```

<!-- ======================================================= -->

## Rdata файл ба lists

`.Rdata` файлууд олон R обьектыг хадгалах боломжтой. Тухайлбал олон хүснэгт, тооцоолн загварчлалын үр дүн, lists гэх мэт файлууд бүгд орж болно. Тодораой төсөл дээр бусадтай хамтран ажиллаж байгаа үед их ашигтай байдаг.

Жишээнд "my_objects.Rdata" гэсэн экспорт хийсэн файлд олон R обьектуудыг нэг дор хадгалахыг харуулав.


```r
rio::export(my_list, my_dataframe, my_vector, "my_objects.Rdata")
```

Анхааруулга: Хэрэв та list импорт хийх бол **rio** багцын [import_list()](https://rdrr.io/pkg/rio/man/import_list.html) --ыг ашигласнаар тухайн list-ийн төрөл, чанар, бүтцийг яг хэвээр нь хадгалах боломжтой.


```r
rio::import_list("my_list.Rdata")
```

<!-- ======================================================= -->

## График хадгалах

`ggplot()`-ээр үүсгэсэн график хадгалах талаар [ggplot basics](https://epirhandbook.com/ggplot-basics.html#ggplot-basics) гэсэн хуудаст илүү нарийн заасан буй.

Товчхондоо график үүсгэсний дараа `ggsave("my_plot_filepath_and_name.png")` гэсэн кодыг уншуулж хадгалдаг.  Өмнө нь хадгалагдсан байсан графикийн нэрийг `plot =` аргументэд өгч болно. Эсвэл файлын байрлах замыг (өргөтгөлтэй нь хамт ) оруулж хамгийн сүүлд үзүүлсэн графикийг хадгална. Графикийн өргөн, урт, нэгж, нарийвчлал зэргийг `width =`, `height =`, `units =`, `dpi =` аар тохируулж болно.

Халдварын тархалт зэрэг тор (network) хэлбэрийн графикийг хадгалах талаар [Transmission
chains](https://epirhandbook.com/transmission-chains.html#transmission-chains) хуудаст оруулсан.

<!-- ======================================================= -->

## Эх сурвалж материал

[R Data Import/Export Manual](https://cran.r-project.org/doc/manuals/r-release/R-data.html)\
[R 4 Data Science chapter on data import](https://r4ds.had.co.nz/data-import.html#data-import)\
[ggsave() documentation](https://ggplot2.tidyverse.org/reference/ggsave.html)

Дараах хүснэгтийг **rio** багцын онлайн [vignette](https://cran.r-project.org/web/packages/rio/vignettes/rio.html) --ээс авсан хүснэгт. Файлын өргөтгөл тус бүрт **rio** багц импорт, экспорт хийхдээ файлын өргөтгөлөөс хамаарч ямар өөр багцыг далдуур ажиллуулдаг болохыг файл тус бүрт харруулсан. Мөн ингэж гүйцэтгэх үүрэг **rio**-ын default хувилбарт орсон эсэхийг тайлбарласан.

| Format                              | Typical Extension       | Import Package       | Export Package | Installed by Default |
|-------------------------------------|-------------------------|----------------------|----------------|----------------------|
| Comma-separated data                | .csv                    | data.table `fread()` | data.table     | Yes                  |
| Pipe-separated data                 | .psv                    | data.table `fread()` | data.table     | Yes                  |
| Tab-separated data                  | .tsv                    | data.table `fread()` | data.table     | Yes                  |
| SAS                                 | .sas7bdat               | haven                | haven          | Yes                  |
| SPSS                                | .sav                    | haven                | haven          | Yes                  |
| Stata                               | .dta                    | haven                | haven          | Yes                  |
| SAS                                 | XPORT                   | .xpt                 | haven          | haven                |
| SPSS Portable                       | .por                    | haven                |                | Yes                  |
| Excel                               | .xls                    | readxl               |                | Yes                  |
| Excel                               | .xlsx                   | readxl               | openxlsx       | Yes                  |
| R syntax                            | .R                      | base                 | base           | Yes                  |
| Saved R objects                     | .RData, .rda            | base                 | base           | Yes                  |
| Serialized R objects                | .rds                    | base                 | base           | Yes                  |
| Epiinfo                             | .rec                    | foreign              |                | Yes                  |
| Minitab                             | .mtp                    | foreign              |                | Yes                  |
| Systat                              | .syd                    | foreign              |                | Yes                  |
| "XBASE"                             | database files          | .dbf                 | foreign        | foreign              |
| Weka Attribute-Relation File Format | .arff                   | foreign              | foreign        | Yes                  |
| Data Interchange Format             | .dif                    | utils                |                | Yes                  |
| Fortran data                        | no recognized extension | utils                |                | Yes                  |
| Fixed-width format data             | .fwf                    | utils                | utils          | Yes                  |
| gzip comma-separated data           | .csv.gz                 | utils                | utils          | Yes                  |
| CSVY (CSV + YAML metadata header)   | .csvy                   | csvy                 | csvy           | No                   |
| EViews                              | .wf1                    | hexView              |                | No                   |
| Feather R/Python interchange format | .feather                | feather              | feather        | No                   |
| Fast Storage                        | .fst                    | fst                  | fst            | No                   |
| JSON                                | .json                   | jsonlite             | jsonlite       | No                   |
| Matlab                              | .mat                    | rmatio               | rmatio         | No                   |
| OpenDocument Spreadsheet            | .ods                    | readODS              | readODS        | No                   |
| HTML Tables                         | .html                   | xml2                 | xml2           | No                   |
| Shallow XML documents               | .xml                    | xml2                 | xml2           | No                   |
| YAML                                | .yml                    | yaml                 | yaml           | No                   |
| Clipboard default is tsv            |                         | clipr                | clipr          | No                   |


<!--chapter:end:new_pages/importing.Rmd-->

# (PART) Data Management {.unnumbered}


<!--chapter:end:new_pages/cat_data_management.Rmd-->


# Cleaning data and core functions {}

Placeholder


### Core functions {.unnumbered}  
### Nomenclature {.unnumbered}  
## Cleaning pipeline
## Load packages  
## Import data  
### Import {.unnumbered}  
### Review {.unnumbered}  
## Column names {} 
### Labels {.unnumbered}  
### Automatic cleaning {.unnumbered}  
### Manual name cleaning {.unnumbered}  
#### Rename by column position {.unnumbered} 
#### Rename via `select()` and `summarise()` {.unnumbered}  
### Other challenges {.unnumbered}  
#### Empty Excel column names {.unnumbered} 
#### Merged Excel column names and cells {.unnumbered}  
## Select or re-order columns {} 
### Keep columns {.unnumbered}  
### "tidyselect" helper functions {#clean_tidyselect .unnumbered}  
### Remove columns {.unnumbered} 
### Standalone {.unnumbered}
#### Add to the pipe chain {.unnumbered}  
## Deduplication
## Column creation and transformation { }
### New columns {.unnumbered}
### Convert column class {.unnumbered}
### Grouped data {.unnumbered}  
### Transform multiple columns {#clean_across .unnumbered}
#### `across()` column selection {.unnumbered}  
#### `across()` functions {.unnumbered}
### `coalesce()` {.unnumbered}  
### Cumulative math {.unnumbered}
### Using **base** R {.unnumbered}  
### Add to pipe chain {.unnumbered}  
## Re-code values
### Specific values {.unnumbered}  
### By logic {.unnumbered}
### Simple logic {.unnumbered}  
#### `replace()` {.unnumbered}  
#### `ifelse()` and `if_else()` {.unnumbered}  
### Complex logic {#clean_case_when .unnumbered}  
### Missing values {.unnumbered} 
### Cleaning dictionary {.unnumbered}
#### Add to pipe chain {.unnumbered}  
## Numeric categories {#num_cats}
### Review distribution {.unnumbered}
### `age_categories()` {.unnumbered}
### `cut()` {.unnumbered}
### Quantile breaks {.unnumbered}  
### Evenly-sized groups {.unnumbered}  
### `case_when()` { .unnumbered}
### Add to pipe chain {.unnumbered}  
## Add rows  
### One-by-one {.unnumbered}  
### Bind rows {.unnumbered}  
## Filter rows {  }
### Simple filter {.unnumbered} 
### Filter out missing values {.unnumbered}  
### Filter by row number {.unnumbered}  
### Complex filter {.unnumbered} 
#### Examine the data  {.unnumbered}  
#### How filters handle missing numeric and date values {.unnumbered}  
#### Design the filter {.unnumbered}  
### Standalone {.unnumbered}  
### Quickly review records {.unnumbered} 
#### Add to pipe chain {.unnumbered}  
## Row-wise calculations  
## Arrange and sort  

<!--chapter:end:new_pages/cleaning.Rmd-->


# Working with dates {}

Placeholder


## Preparation
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
## Current date  
## Convert to Date  
### **base** R {.unnumbered}  
### **lubridate** {.unnumbered}  
### Combine columns {.unnumbered}  
## Excel dates
## Messy dates  
## Working with date-time class  
### Convert dates with times {.unnumbered}  
### Convert times alone {.unnumbered}  
### Extract time {.unnumbered}  
## Working with dates   
### Extract date components {.unnumbered}  
### Date math {.unnumbered}  
### Date intervals {.unnumbered}  
## Date display  
### `format()` {.unnumbered}  
### Month-Year {.unnumbered}  
## Epidemiological weeks {#dates_epi_wks}
### **lubridate** {.unnumbered}  
### Weekly counts {.unnumbered}  
### Epiweek alternatives {.unnumbered}  
## Converting dates/time zones
## Lagging and leading calculations  
## Resources  

<!--chapter:end:new_pages/dates.Rmd-->


# Characters and strings { }  

Placeholder


## Preparation { }
### Load packages {.unnumbered}  
### Import data  {.unnumbered}  
## Unite, split, and arrange { }
### Combine strings {.unnumbered}
### Dynamic strings {.unnumbered}
### Unite columns  {#str_unite .unnumbered}
### Split {.unnumbered}  
### Split columns {.unnumbered}  
### Arrange alphabetically {.unnumbered} 
### base R functions {.unnumbered}
## Clean and standardise  
### Change case {.unnumbered}
### Pad length  {#str_pad .unnumbered}
### Truncate {.unnumbered} 
### Standardize length {.unnumbered}
### Remove leading/trailing whitespace {.unnumbered}  
### Remove repeated whitespace within {.unnumbered}  
### Wrap into paragraphs {.unnumbered}  
## Handle by position { }
### Extract by character position {.unnumbered}  
### Extract by word position {.unnumbered} 
### Replace by character position {.unnumbered} 
### Evaluate length  {.unnumbered}
## Patterns { }
### Detect a pattern {.unnumbered}
#### Convert commas to periods {.unnumbered}  
### Replace all {.unnumbered}  
### Detect within logic {.unnumbered}
### Locate pattern position {.unnumbered}  
### Extract a match {.unnumbered}  
### Subset and count {.unnumbered}  
### Regex groups {.unnumbered}
## Special characters  
## Regular expressions (regex) 
## Regex and special characters { } 
## Resources { }

<!--chapter:end:new_pages/characters_strings.Rmd-->


# Factors {}

Placeholder


## Preparation  
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
### New categorical variable {#fct_newcat .unnumbered}  
#### Create column {.unnumbered}  
#### Default value order {.unnumbered}  
## Convert to factor  
## Add or drop levels  
### Add {#fct_add .unnumbered}
### Drop {.unnumbered}  
## Adjust level order {#fct_adjust} 
### Manually {.unnumbered} 
### Within a plot {.unnumbered}  
### Reverse {.unnumbered}  
### By frequency {.unnumbered}  
### By appearance {.unnumbered}  
### By summary statistic of another column {.unnumbered}  
### By "end" value {.unnumbered}  
## Missing values {#fct_missing}  
## Combine levels  
### Manually {.unnumbered}  
### Reduce into "Other" {.unnumbered}  
### Reduce by frequency {.unnumbered}
## Show all levels  
### In plots {.unnumbered}  
### In tables {.unnumbered}  
## Epiweeks  
### Epiweeks in a plot {.unnumbered}  
### Epiweeks in the data {.unnumbered}  
## Resources {} 

<!--chapter:end:new_pages/factors.Rmd-->


# Pivoting data {}

Placeholder


## Preparation  
### Load packages {.unnumbered}  
### Import data {.unnumbered}
### Malaria count data {-}  
### Linelist case data {-}  
## Wide-to-long {}
### "Wide" format {.unnumbered}
### `pivot_longer()` {.unnumbered}
### Standard pivoting {.unnumbered}  
### Pivoting data of multiple classes {.unnumbered}
## Long-to-wide {}
### Data {.unnumbered}
### Pivot wider {.unnumbered}  
## Fill 
### Data {.unnumbered}
### `fill()` {.unnumbered}
## Resources  

<!--chapter:end:new_pages/pivoting.Rmd-->


# Grouping data { }  

Placeholder


## Preparation {  }
### Load packages {.unnumbered}  
### Import data {.unnumbered}
## Grouping {  }
### Unique groups {.unnumbered}  
### New columns {.unnumbered} 
### Add/drop grouping columns {.unnumbered}  
## Un-group  
## Summarise {#group_summarise} 
## Counts and tallies  
### `tally()` {.unnumbered}  
### `count()`  {.unnumbered}  
### Add counts {.unnumbered}  
### Add totals {.unnumbered} 
## Grouping by date  
### Linelist cases into days  {.unnumbered}  
### Linelist cases into weeks {.unnumbered}  
### Linelist cases into months {.unnumbered}
### Daily counts into weeks {.unnumbered}
#### Daily counts into months {.unnumbered}
## Arranging grouped data
## Filter on grouped data
### `filter()` {.unnumbered}
### Slice rows per group {.unnumbered} 
### Filter on group size {#group_filter_grp_size .unnumbered} 
## Mutate on grouped data  
## Select on grouped data  
## Resources {  }

<!--chapter:end:new_pages/grouping.Rmd-->


# Joining data { }  

Placeholder


## Preparation { }
### Load packages {.unnumbered}
### Import data {.unnumbered}
### Example datasets {.unnumbered}
#### "Miniature" case linelist {#joins_llmini .unnumbered}  
#### Hospital information data frame {#joins_hosp_info .unnumbered}  
### Pre-cleaning {.unnumbered}
## **dplyr** joins { }
### General syntax {.unnumbered}
### Left and right joins {.unnumbered}  
#### "Should I use a right join, or a left join?" {.unnumbered}  
### Full join {.unnumbered} 
### Inner join {.unnumbered} 
### Semi join {.unnumbered} 
### Anti join {.unnumbered} 
#### Simple `anti_join()` example {.unnumbered}  
#### Complex `anti_join()` example {.unnumbered}  
## Probabalistic matching { }
### Probabilistic matching {.unnumbered}  
### Probabilistic deduplication {.unnumbered}  
## Binding and aligning  
### Bind rows {.unnumbered}
### Bind columns {.unnumbered}
#### Use `match()` to align ordering {.unnumbered}  
## Resources { }

<!--chapter:end:new_pages/joining_matching.Rmd-->


# De-duplication {}  

Placeholder


## Preparation { }
### Load packages {.unnumbered}
### Import data {.unnumbered}
#### Here is the data frame {#dedup_data .unnumbered}  
## Deduplication { }
### Examine duplicate rows {.unnumbered}  
### Keep only unique rows  {.unnumbered}
### Deduplicate elements in a vector {.unnumbered}  
### Using **base** R {.unnumbered}
## Slicing { }
### Slice with groups  {.unnumbered}
### Keep all but mark them  {.unnumbered}
### Calculate row completeness {.unnumbered} 
## Roll-up values {#str_rollup}
### Roll-up values into one row {.unnumbered}  
### Overwrite values/hierarchy {.unnumbered} 
## Probabilistic de-duplication  
## Resources { }

<!--chapter:end:new_pages/deduplication.Rmd-->


# Iteration, loops, and lists { }  

Placeholder


## Preparation {  }
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
## *for loops* {  }
### *for loops* in R {#iter_loops .unnumbered}  
### Core components {.unnumbered}   
### Sequence {.unnumbered}  
### Operations  {.unnumbered}  
### Container {.unnumbered}
### Printing {.unnumbered}  
### Testing your for loop {.unnumbered}
### Looping plots {.unnumbered}
### Tracking progress of a loop {.unnumbered} 
## **purrr** and lists {#iter_purrr}
### Load packages {.unnumbered}  
### `map()` {.unnumbered}  
#### Example - import and combine Excel sheets {#iter_combined .unnumbered}  
### Split dataset and export {.unnumbered}  
#### Split dataset {.unnumbered}  
##### More than one `group_split()` column {.unnumbered}  
#### Export as Excel sheets {.unnumbered}  
#### Export as CSV files {.unnumbered}  
### Custom functions {.unnumbered}  
### Mapping a function across columns {.unnumbered}  
### Extract from lists {.unnumbered}  
#### Names of elements {.unnumbered}  
#### Elements by name or position {.unnumbered}  
#### `pluck()` {.unnumbered}  
### Convert list to data frame {.unnumbered}  
### Discard, keep, and compact lists {.unnumbered}  
### `pmap()` {.unnumbered}
## Apply functions  
## Resources { }

<!--chapter:end:new_pages/iteration.Rmd-->

# (PART) Analysis {.unnumbered}



<!--chapter:end:new_pages/cat_analysis.Rmd-->


# Descriptive tables { }

Placeholder


## Preparation {  }
### Load packages {.unnumbered}
### Import data {.unnumbered}
## Browse data {  }
### **skimr** package {.unnumbered}
### Summary statistics {.unnumbered} 
## **janitor** package {#tbl_janitor}  
### Simple tabyl {.unnumbered}  
### Cross-tabulation {.unnumbered}  
### "Adorning" the tabyl {#tbl_adorn .unnumbered}  
### Printing the tabyl {.unnumbered}
### Use on other tables {.unnumbered}  
### Saving the tabyl {.unnumbered}  
### Statistics {#janitor_age_out_stats .unnumbered}  
### Other tips {.unnumbered}  
## **dplyr** package   
### Get counts {.unnumbered}  
### Show all levels {.unnumbered}  
### Proportions {#tbl_dplyr_prop .unnumbered}  
### Plotting {.unnumbered}  
### Summary statistics {.unnumbered}  
### Conditional statistics {.unnumbered}  
### Glueing together {.unnumbered}  
#### Percentiles {.unnumbered}  
### Summarise aggregated data {.unnumbered}  
### `across()` multiple columns {.unnumbered}  
### Pivot wider {#tbls_pivot_wider .unnumbered}
### Total rows {#tbl_dplyr_totals .unnumbered}  
#### **janitor**'s `adorn_totals()` {.unnumbered}  
#### `summarise()` on "total" data and then `bind_rows()` {.unnumbered}  
## **gtsummary** package {#tbl_gt}   
### Summary table {.unnumbered}
### Adjustments {.unnumbered}  
### Multi-line stats for continuous variables {.unnumbered}  
## **base** R   
### Proportions {.unnumbered}  
### Totals {.unnumbered}  
### Convert to data frame {.unnumbered}  
## Resources {  }

<!--chapter:end:new_pages/tables_descriptive.Rmd-->


# Simple statistical tests { }

Placeholder


## Preparation {  }
### Load packages {.unnumbered}
### Import data {.unnumbered}
## **base** R {}
### T-tests {.unnumbered} 
### Shapiro-Wilk test {.unnumbered}  
### Wilcoxon rank sum test {.unnumbered}
### Kruskal-Wallis test {.unnumbered}
### Chi-squared test {.unnumbered} 
## **rstatix** package {}
### Summary statistics {.unnumbered}  
### T-test {.unnumbered}  
### Shapiro-Wilk test {.unnumbered}  
### Wilcoxon rank sum test {.unnumbered}  
### Kruskal-Wallis test {.unnumbered}  
### Chi-squared test {.unnumbered}  
## `gtsummary` package {#stats_gt}
### Chi-squared test {.unnumbered}
### T-tests {.unnumbered} 
### Wilcoxon rank sum test{.unnumbered}
### Kruskal-wallis test {.unnumbered}
## Correlations 
## Resources {  }

<!--chapter:end:new_pages/stat_tests.Rmd-->


# Univariate and multivariable regression { }

Placeholder


## Preparation {  }
### Load packages {.unnumbered}
### Import data {.unnumbered}
### Clean data {.unnumbered}
#### Store explanatory variables {.unnumbered}  
#### Convert to 1's and 0's  {.unnumbered}   
#### Drop rows with missing values {.unnumbered}  
## Univariate {  }
### **base** R {.unnumbered}
#### Linear regression {.unnumbered}  
#### Logistic regression {.unnumbered}  
#### Univariate `glm()` {.unnumbered}
#### Printing results {.unnumbered}
#### Looping multiple univariate models {.unnumbered}  
### **gtsummary** package {#reg_gt_uni .unnumbered}
## Stratified {  }
## Multivariable  
### Conduct multivariable {.unnumbered}  
#### Building the model {.unnumbered}  
### Combine univariate and multivariable {.unnumbered}
#### Combine with **gtsummary**  {.unnumbered}  
#### Combine with **dplyr** {.unnumbered}  
## Forest plot {  }
### **ggplot2** package {.unnumbered}
### **easystats** packages {.unnumbered}
## Resources {  }

<!--chapter:end:new_pages/regression.Rmd-->


# Missing data { }

Placeholder


## Preparation { }
### Load packages {.unnumbered}  
### Import data {.unnumbered}
### Convert missing on import {.unnumbered}  
## Missing values in R { }
### `NA` {.unnumbered}  
### Versions of `NA` {.unnumbered}  
### `NULL` {.unnumbered}  
### `NaN` {.unnumbered}  
### `Inf` {.unnumbered}  
### Examples {.unnumbered}  
## Useful functions { }
### `is.na()` and `!is.na()` {.unnumbered}  
### `na.omit()` {.unnumbered}  
### `drop_na()` {.unnumbered}  
### `na.rm = TRUE` {.unnumbered}  
## Assess missingness in a data frame { }
### Quantifying missingness {.unnumbered}
### Visualizing missingness {.unnumbered}  
### Explore and visualize missingness relationships {.unnumbered} 
### "Shadow" columns {.unnumbered}
## Using data with missing values  
### Filter out rows with missing values {.unnumbered}
### Handling `NA` in `ggplot()` {.unnumbered}
### `NA` in factors {.unnumbered}
## Imputation { }
### Types of missing data {.unnumbered}
### Useful packages {.unnumbered}
### Mean Imputation {.unnumbered}
### Regression imputation {.unnumbered}
### LOCF and BOCF {.unnumbered}
### Multiple Imputation {.unnumbered}
## Resources { }

<!--chapter:end:new_pages/missing_data.Rmd-->


# Standardised rates { }  

Placeholder


## Overview  
## Preparation {  }
### Load packages {.unnumbered}
### Load population data {.unnumbered}  
### Load death counts {.unnumbered}  
### Clean populations and deaths {.unnumbered}  
### Load reference population {.unnumbered}  
### Clean reference population {.unnumbered}
### Create dataset with standard population {#standard_all .unnumbered}  
## **dsr** package {  }
### Standardized rates {.unnumbered}
### Standardized rate ratios {.unnumbered}
### Standardized rate difference {.unnumbered}
## **PHEindicatormethods** package {#standard_phe  }
### Directly standardized rates {.unnumbered}
### Indirectly standardized rates {#standard_indirect .unnumbered}
## Resources {  }

<!--chapter:end:new_pages/standardization.Rmd-->


# Moving averages { }  

Placeholder


## Preparation {  }
### Load packages {.unnumbered}
### Import data {.unnumbered}
## Calculate with **slider** {  }
### Rolling by date  {#roll_index .unnumbered}  
### Indexed data {.unnumbered}  
### Rolling by group {#roll_slider_group .unnumbered}  
## Calculate with **tidyquant** within `ggplot()` {  }
## Resources {  }

<!--chapter:end:new_pages/moving_average.Rmd-->


# Time series and outbreak detection { }  

Placeholder


## Overview {  }
## Preparation {  }
### Packages {.unnumbered}
### Load data {.unnumbered}
### Clean data {.unnumbered}
### Download climate data {.unnumbered} 
### Load climate data {.unnumbered}
## Time series data {  }
### Duplicates {.unnumbered}
### Missings {.unnumbered}
## Descriptive analysis {  }
### Moving averages {#timeseries_moving .unnumbered}
### Periodicity {.unnumbered}
### Decomposition {.unnumbered}
### Autocorrelation {.unnumbered}
## Fitting regressions {  }
### Fourier terms {.unnumbered}
### Negative binomial {.unnumbered}
### Residuals {.unnumbered}
## Relation of two time series {  }
### Merging datasets {.unnumbered}
### Descriptive analysis {.unnumbered}
### Lags and cross-correlation {.unnumbered}
### Negative binomial with two variables {.unnumbered}
#### Residuals {.unnumbered}
## Outbreak detection {  }
### **trending** package {.unnumbered}
#### Cut-off date { -}
#### Add rows {.unnumbered}
#### Fourier terms {.unnumbered}
#### Split data and fit regression {.unnumbered}
#### Prediction validation {.unnumbered}
### **surveillance** package {.unnumbered}
#### Farrington method {.unnumbered}
#### GLRNB method {.unnumbered}
## Interrupted timeseries {  }
## Resources {  }

<!--chapter:end:new_pages/time_series.Rmd-->


# Epidemic modeling { }  

Placeholder


## Overview {  }
## Preparation {  }
## Estimating R<sub>t</sub> {  }
### EpiNow2 vs. EpiEstim {.unnumbered}
### EpiNow2 {.unnumbered}
#### Estimating delay distributions {.unnumbered}
#### Running **EpiNow2** {.unnumbered}
#### Analysing outputs {.unnumbered}
### EpiEstim {.unnumbered}
#### Using serial interval estimates from the literature {.unnumbered}
#### Using serial interval estimates from the data {.unnumbered}
#### Specifying estimation time windows {.unnumbered}
#### Analysing outputs {.unnumbered}
## Projecting incidence {  }
### EpiNow2 {.unnumbered}
### projections {.unnumbered}
#### Using serial interval estimates from the literature {.unnumbered}
#### Using serial interval estimates from the data {.unnumbered}
#### Projecting incidence {.unnumbered}
## Resources {  }

<!--chapter:end:new_pages/epidemic_models.Rmd-->


# Contact tracing { }

Placeholder


## Preparation
### Load packages {.unnumbered}  
### Import data {.unnumbered}
#### Case data {.unnumbered}  
#### Contacts data {.unnumbered}  
#### Follow-up data {.unnumbered}  
#### Relationships data {.unnumbered}  
## Descriptive analyses  
### Demographics {.unnumbered}  
#### Age and Gender of contacts {.unnumbered}  
### Contacts per case {.unnumbered}  
## Contact Follow Up  
### Data cleaning {.unnumbered}  
### Plot over time {.unnumbered}  
### Daily individual tracking  {.unnumbered}  
### Analyse by group {.unnumbered}  
## KPI Tables  
## Transmission Matrices  
## Resources  

<!--chapter:end:new_pages/contact_tracing.Rmd-->


# Survey analysis { }  

Placeholder


## Overview {  }
## Preparation {  }
### Packages {.unnumbered}
### Load data {.unnumbered}
### Clean data {.unnumbered}
## Survey data {  }
## Observation time {  }
## Weighting {  }
## Survey design objects {  }
### **Survey** package  
### **Srvyr** package  
## Descriptive analysis {  }
### Sampling bias 
### Demographic pyramids 
### Alluvial/sankey diagram
## Weighted proportions {  }
### **Survey** package 
### **Srvyr** package 
### **Sitrep** package 
### **Gtsummary** package
## Weighted ratios {  }
### **Survey** package 
### **Srvyr** package 
## Resources {  }

<!--chapter:end:new_pages/survey_analysis.Rmd-->


# Survival analysis { }  

Placeholder


## Overview {}
## Preparation {  }
### Load packages {.unnumbered}  
### Import dataset {.unnumbered}  
### Data management and transformation {.unnumbered}
## Basics of survival analysis {}
### Building a surv-type object {.unnumbered}
### Running initial analyses {.unnumbered}
### Cumulative hazard {.unnumbered}  
### Plotting Kaplan-Meir curves  {.unnumbered}
## Comparison of survival curves 
### Log rank test {.unnumbered}
## Cox regression analysis {}
### Fitting a Cox model {.unnumbered}
### Forest plots {.unnumbered}
## Time-dependent covariates in survival models {}
### Time-dependent covariate setup {.unnumbered} 
#### Add unique patient identifier {.unnumbered}  
#### Expand patient rows {.unnumbered}  
### Cox regression with time-dependent covariates {.unnumbered} 
## Resources {  }

<!--chapter:end:new_pages/survival_analysis.Rmd-->


# GIS basics { }  

Placeholder


## Overview {  }
## Key terms {}  
### GIS software {.unnumbered}
### Spatial data {.unnumbered}
### Visualizing spatial data {.unnumbered}
## Getting started with GIS  
### Types of maps for visualizing your data {.unnumbered}
## Preparation {  }
### Load packages {.unnumbered}  
### Sample case data {.unnumbered}
### Admin boundary shapefiles {.unnumbered}  
### Population data {.unnumbered}  
### Health Facilities {.unnumbered}
## Plotting coordinates {  }
## Spatial joins {}
### Points in polygon {.unnumbered}
### Nearest neighbor {.unnumbered}
### Buffers {.unnumbered} 
### Other spatial joins {.unnumbered}  
## Choropleth maps {}  
## Mapping with ggplot2
## Basemaps { }
### OpenStreetMap {.unnumbered} 
## Contoured density heatmaps {}
### Time series heatmap {.unnumbered}
## Spatial statistics
### Spatial relationships {.unnumbered}  
### Spatial autocorrelation {.unnumbered}  
### Spatial regression {.unnumbered}  
## Resources {  }

<!--chapter:end:new_pages/gis.Rmd-->

# (PART) Data Visualization {.unnumbered}


<!--chapter:end:new_pages/cat_data_viz.Rmd-->


# Tables for presentation { }  

Placeholder


## Preparation {  }
### Load packages {.unnumbered} 
### Import data {.unnumbered}  
### Prepare table {.unnumbered}  
## Basic flextable {  }
### Create a flextable {.unnumbered}  
### Column width {.unnumbered}
### Column headers {.unnumbered}
### Borders and background {.unnumbered}  
### Font and alignment {.unnumbered}
### Merge cells {.unnumbered}  
### Background color {.unnumbered}
## Conditional formatting {  }
## All code together {#tbl_pres_all}  
## Saving your table {  }
### Save single table {.unnumbered}
### Print table in R markdown {.unnumbered}  
## Resources {  }

<!--chapter:end:new_pages/tables_presentation.Rmd-->


# ggplot basics {}

Placeholder


## Preparation {}
### Load packages {.unnumbered}
### Import data {.unnumbered}  
### General cleaning {.unnumbered}
### Pivoting longer {.unnumbered}
## Basics of ggplot {}
## `ggplot()`  
## Geoms  
## Mapping data to the plot {#ggplot_basics_mapping}  
### Plot aesthetics {.unnumbered}  
### Set to a static value {.unnumbered}  
### Scaled to column values {.unnumbered}  
### Where to make mapping assignments {#ggplot_basics_map_loc .unnumbered}
### Groups {#ggplotgroups .unnumbered}  
## Facets / Small-multiples {#ggplot_basics_facet}  
### `facet_wrap()` {.unnumbered}
### `facet_grid()` {.unnumbered}  
### Free or fixed axes {.unnumbered}  
### Factor level order in facets {.unnumbered}  
## Storing plots  
### Saving plots {.unnumbered}
### Modifying saved plots {.unnumbered}  
### Exporting plots {.unnumbered}   
## Labels 
## Themes {#ggplot_basics_themes} 
### Complete themes {.unnumbered}  
### Modify theme {.unnumbered}  
## Colors  
## Piping into **ggplot2**   
## Plot continuous data
### Histograms {.unnumbered}
### Box plots {.unnumbered}
### Violin, jitter, and sina plots {.unnumbered}
### Two continuous variables  {.unnumbered}
### Three continuous variables {.unnumbered}  
## Plot categorical data  
### Preparation  {.unnumbered}
#### Data structure {.unnumbered}  
#### Column class and value ordering {.unnumbered}  
### `geom_bar()` {#ggplot_basics_bars .unnumbered}  
### `geom_col()` {.unnumbered}  
### `geom_histogram()` {.unnumbered}  
## Resources  

<!--chapter:end:new_pages/ggplot_basics.Rmd-->


# ggplot tips {}

Placeholder


## Preparation {}
### Load packages {.unnumbered}
### Import data {.unnumbered}  
## Scales for color, fill, axes, etc. {#ggplot_tips_colors}
### Color schemes
### Scales {#ggplot_tips_scales .unnumbered}  
### Scale arguments {.unnumbered}  
### Manual adjustments {.unnumbered}  
### Continuous axes scales {.unnumbered}  
#### Display percents {.unnumbered}  
#### Log scale {.unnumbered}  
### Gradient scales {.unnumbered}  
### Palettes {.unnumbered}  
#### Colorbrewer and Viridis {.unnumbered}
## Change order of discrete variables {}  
#### **ggthemr** {.unnnumbered}  
## Contour lines  
## Marginal distributions  
## Smart Labeling {}  
## Time axes {}
## Highlighting {}
## Plotting multiple datasets  
## Combine plots {}
### `plot_grid()` {.unnumbered}
### Combine legends {.unnumbered}  
### Inset plots {.unnumbered} 
## Dual axes {}
## Packages to help you  
### Point-and-click **ggplot2** with **equisse**  {.unnumbered}
## Miscellaneous  
### Numeric display {.unnumbered}  
## Resources

<!--chapter:end:new_pages/ggplot_tips.Rmd-->


# Epidemic curves { }  

Placeholder


## Preparation
### Packages {.unnumbered}  
### Import data {.unnumbered}
### Set parameters {.unnumbered}
### Verify dates {.unnumbered}
## Epicurves with **incidence2** package { }
### Simple example {.unnumbered}
### Change time interval of case aggregation {.unnumbered}  
### Groups {.unnumbered}
### Filtered data {.unnumbered}
### Aggregated counts {.unnumbered}
### Facets/small multiples {.unnumbered}  
### Modifications with `plot()` {.unnumbered} 
### Modifications with ggplot2 {.unnumbered}
### Change colors  {.unnumbered}  
#### Specify a palette {.unnumbered}  
#### Specify manually {.unnumbered}  
### Adjust level order {.unnumbered}  
### Vertical gridlines {.unnumbered}  
### Cumulative incidence {.unnumbered}  
### Rolling average  {.unnumbered}
## Epicurves with ggplot2 { }
### Specify case bins {.unnumbered}  
### Weekly epicurve example {.unnumbered}  
#### Sunday weeks {.unnumbered}  
### Group/color by value {.unnumbered}
### Adjust colors {.unnumbered}  
### Adjust level order {.unnumbered}  
### Adjust legend {.unnumbered}
### Bars side-by-side {.unnumbered}  
### Axis limits {.unnumbered}  
### Date-axis labels/gridlines {.unnumbered} 
#### Demonstrations {.unnumbered}
### Aggregated data {.unnumbered} 
#### Plotting daily counts {.unnumbered}  
#### Plotting weekly counts {.unnumbered}
### Moving averages {.unnumbered}
### Faceting/small-multiples {.unnumbered}
#### Total epidemic in facet background {.unnumbered}
#### One facet with data {.unnumbered}  
## Tentative data  
### Using `annotate()` {.unnumbered}
### Bars color {.unnumbered}  
## Multi-level date labels  
## Dual-axis { }  
## Cumulative Incidence {}
## Resources { }

<!--chapter:end:new_pages/epicurves.Rmd-->


# Demographic pyramids and Likert-scales {}  

Placeholder


## Preparation {}
### Load packages {.unnumbered}
### Import data {.unnumbered}  
### Cleaning {.unnumbered}  
## **apyramid** package {}
### Linelist data {.unnumbered}  
#### Missing values {.unnumbered}  
#### Proportions, colors, & aesthetics {.unnumbered}  
### Aggregated data {.unnumbered}  
## `ggplot()` {#demo_pyr_gg}
### Preparation {.unnumbered}
### Constructing the plot {.unnumbered} 
### Compare to baseline  {.unnumbered} 
## Likert scale {}
## Resources {}

<!--chapter:end:new_pages/age_pyramid.Rmd-->


# Heat plots { }  

Placeholder


## Preparation { }
### Load packages {.unnumbered}  
## Transmission matrix  
### Data preparation {.unnumbered}  
#### Make cases data frame {.unnumbered} 
#### Make infectors data frame {.unnumbered}  
### Create heat plot {.unnumbered}  
## Reporting metrics over time { }
### Data preparation {.unnumbered}
#### Aggregate and summarize {.unnumbered}
### Create heat plot {.unnumbered}
### Basic {.unnumbered}  
### Cleaned plot {.unnumbered}
### Ordered y-axis {.unnumbered}  
### Display values {.unnumbered}  
## Resources { }

<!--chapter:end:new_pages/heatmaps.Rmd-->


# Diagrams and charts { }  

Placeholder


## Preparation { }
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
## Flow diagrams { }
### Simple examples {.unnumbered} 
### Syntax  {.unnumbered}
### Complex examples  {.unnumbered}
### Outputs  {.unnumbered}
### Parameterized figures {.unnumbered} 
## Alluvial/Sankey Diagrams { }
### Load packages {.unnumbered}  
### Plotting from dataset {.unnumbered} 
## Event timelines { }
## DAGs { }
## Resources { }

<!--chapter:end:new_pages/diagrams.Rmd-->


# Combinations analysis { }  

Placeholder


## Preparation {  }
### Load packages {.unnumbered}
### Import data {.unnumbered}  
### Re-format values {.unnumbered}  
## **ggupset** {  }
## `UpSetR` {  }
## Resources {  }

<!--chapter:end:new_pages/combination_analysis.Rmd-->


# Transmission chains { }

Placeholder


## Overview {  }
## Preparation {  }
### Load packages {.unnumbered}  
### Import data {.unnumbered}
### Creating an epicontacts object {.unnumbered}
## Handling {  }
### Subsetting {.unnumbered}
### Accessing IDs {.unnumbered}
## Visualization {  }
### Basic plotting {.unnumbered}
#### Visualising node attributes {.unnumbered}
#### Visualising edge attributes {.unnumbered}
### Temporal axis {.unnumbered}
#### Specifying transmission tree shape {.unnumbered}
#### Saving plots and figures {.unnumbered}
### Timelines {.unnumbered}
## Analysis {  }
### Summarising {.unnumbered}
### Pairwise characteristics {.unnumbered}
### Identifying clusters {.unnumbered}
### Calculating degrees {.unnumbered}
## Resources {  }

<!--chapter:end:new_pages/transmission_chains.Rmd-->


# Phylogenetic trees {}  

Placeholder


## Overview {}
## Preparation {}
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
### Clean and inspect {.unnumbered}  
## Simple tree visualization {}
### Different tree layouts {.unnumbered}  
### Simple tree plus sample data {.unnumbered}  
## Tree manipulation {}
### Zoom in {.unnumbered}  
### Collapsing branches {.unnumbered} 
### Subsetting a tree {.unnumbered} 
### Rotating nodes in a tree {.unnumbered} 
### Example subtree with sample data annotation {.unnumbered} 
## More complex trees: adding heatmaps of sample data {.unnumbered}
## Resources {}

<!--chapter:end:new_pages/phylogenetic_trees.Rmd-->


# Interactive plots { }  

Placeholder


## Preparation {  }
### Load packages {.unnumbered}  
### Start with a `ggplot()` {.unnumbered}  
### Import data {.unnumbered}
## Plot with `ggplotly()` {  }
## Modifications {  }
### File size {.unnumbered}  
### Buttons {.unnumbered}  
## Heat tiles {  }
## Resources {  }

<!--chapter:end:new_pages/interactive_plots.Rmd-->

# (PART) Reports and dashboards {.unnumbered}


<!--chapter:end:new_pages/cat_reports_dashboards.Rmd-->


# Reports with R Markdown { }  

Placeholder


## Preparation {  }
## Getting started {  }
### Install rmarkdown R package {.unnumbered}
### Starting a new Rmd file {.unnumbered}
### Important to know {.unnumbered}
## R Markdown components {  }
### YAML metadata {.unnumbered}
### Text {.unnumbered}
#### New lines {.unnumbered}  
#### Case {.unnumbered}  
#### Color {.unnumbered}  
#### Titles and headings {.unnumbered}  
#### Bullets and numbering {.unnumbered}  
#### Comment out text {.unnumbered}
### Code chunks {.unnumbered}
#### In-text R code {.unnumbered}  
### Images {.unnumbered}  
### Tables {.unnumbered}  
### Tabbed sections {.unnumbered}  
## File structure {}
### Self-contained Rmd {.unnumbered}  
#### Source other files {.unnumbered}
### Runfile {.unnumbered}  
### Folder strucutre {.unnumbered}  
## Producing the document  
### Option 1: "Knit" button {.unnumbered}  
### Option 2: `render()` command {.unnumbered}
###  Options 3: **reportfactory**  package {.unnumbered}  
## Parameterised reports {  }
### Setting parameters {.unnumbered}
#### Option 1: Set parameters within YAML {.unnumbered}
#### Option 2: Set parameters within `render()` {.unnumbered}  
#### Option 3: Set parameters using a Graphical User Interface {.unnumbered}  
### Parameterized example {.unnumbered} 
### Parameterisation without `params` {.unnumbered}
## Looping reports  {  }
## Templates  
### Word documents {.unnumbered}
### Powerpoint documents {.unnumbered}
### Integrating templates into the YAML {.unnumbered}
### Formatting HTML files {.unnumbered}
## Dynamic content  
### Tables {.unnumbered}  
### HTML widgets {.unnumbered}
## Resources {  }

<!--chapter:end:new_pages/rmarkdown.Rmd-->


# Organizing routine reports {  }  

Placeholder


## Preparation
### Load packages {.unnumbered}  
## New factory  
## Create a report  
## Compile  
### Compile by name {.unnumbered}  
### Compile by number {.unnumbered}
### Compile all {.unnumbered}
### Compile from sub-folder {.unnumbered}  
### Parameterization {.unnumbered}
### Using a "run-file" {.unnumbered}  
## Outputs  
## Miscellaneous  
### Knit {.unnumbered} 
### Scripts {.unnumbered}  
### Extras {.unnumbered} 
## Resources {  }

<!--chapter:end:new_pages/reportfactory.Rmd-->


# Dashboards with R Markdown { }

Placeholder


## Preparation
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
## Create new R Markdown  
## The script  
### YAML {.unnumbered}  
### Code chunks {.unnumbered}  
### Narrative text {.unnumbered}  
### Headings {.unnumbered}  
## Section attributes  
## Layout {#layout}  
### Pages {.unnumbered}  
### Orientation {.unnumbered}  
### Tabs {.unnumbered} 
## Adding content  
### Text {.unnumbered}  
### Tables {.unnumbered}  
### Plots {.unnumbered}  
### Interactive plots {.unnumbered}  
### HTML widgets {.unnumbered}
## Code organization
## Shiny  
### Settings {.unnumbered}  
### Worked example {.unnumbered}  
### Other examples {.unnumbered}  
## Sharing  
## Resources  

<!--chapter:end:new_pages/flexdashboard.Rmd-->


# Dashboards with Shiny { }  

Placeholder


## Preparation  
### Load packages {.unnumbered}  
### Import data {.unnumbered}  
## The structure of a shiny app {  }
### Basic file structures {.unnumbered}  
### The server and the ui {.unnumbered}
### Before you start to build an app {.unnumbered}
## Building a UI 
## Loading data into our app
## Developing an app server
## Adding more functionality
### Adding static text {.unnumbered}  
### Adding a link {.unnumbered}
### Adding a download button {.unnumbered}
### Adding a facility selector {.unnumbered}  
### Adding another tab with a table {.unnumbered}
## Sharing shiny apps
## Further reading
## Recommended extension packages
## Recommended resources

<!--chapter:end:new_pages/shiny_basics.Rmd-->

# (PART) Miscellaneous {.unnumbered}


<!--chapter:end:new_pages/cat_misc.Rmd-->


# Writing functions  

Placeholder


## Preparation {  }
### Load packages {-}
### Import data {-}
## Functions  
## Why would you use a function? 
## How does R  build functions?
## Basic syntax and structure
## Examples  
### Return proportion tables for several columns {.unnumbered}  
## Using **purrr**: writing functions that can be iteratively applied
### Modify class of multiple columns in a dataset {.unnumbered}  
### Iteratively produce graphs for different levels of a variable {.unnumbered}
### Iteratively produce tables for different levels of a variable {.unnumbered}
## Tips and best Practices for well functioning functions
### Naming and syntax {.unnumbered}
### Column names and tidy evaluation {.unnumbered}  
### Testing and Error handling {.unnumbered}
## Resources

<!--chapter:end:new_pages/writing_functions.Rmd-->


# Directory interactions { }  

Placeholder


## Preparation  
### **fs** package {.unnumbered}  
### Print directory as a dendrogram tree {.unnumbered}  
## List files in a directory  
## File information  
## Check if exists  
### R objects {.unnumbered}  
### Directories {.unnumbered}  
### Files {.unnumbered}  
## Create  
### Directories {.unnumbered}  
### Files {.unnumbered}  
### Create if does not exists {.unnumbered}  
## Delete
### R objects {.unnumbered}  
### Directories {.unnumbered}  
### Files {.unnumbered}  
## Running other files  
### `source()` {.unnumbered}  
### `render()` {.unnumbered}  
### Run files in a directory {.unnumbered}
### Import files in a directory  {.unnumbered}
## **base** R  
## Resources {  }

<!--chapter:end:new_pages/directories.Rmd-->


# Version control and collaboration with Git and Github

Placeholder


## What is Git?
## Why use the combo Git and Github?
### This sounds complicated, I am not a programmer {-}
## Setup
### Install Git {.unnumbered}
### Install an interface (optional but recommended) {.unnumbered}
### Github account {.unnumbered}
## Vocabulary, concepts and basic functions
### Repository {.unnumbered}
### Commits {.unnumbered}
### Branches {.unnumbered}
### Local and remote repositories {.unnumbered}
## Get started: create a new repository
### Start-up files {.unnumbered}
### Create a new repository in Github {.unnumbered}
### Clone from a Github repository {.unnumbered}
#### In Rstudio {.unnumbered}
#### In Github Desktop {.unnumbered}
### New Github repo from existing R project {.unnumbered}
### What does it look like now? {.unnumbered}
#### In RStudio {-}
#### In Github Desktop {-}
## Git + Github workflow
### Process overview {.unnumbered}
## Create a new branch
### In Rstudio Git pane {.unnumbered}
### In Github Desktop {.unnumbered}
### In console {.unnumbered}
## Commit changes
### In Rstudio {.unnumbered}
### In Github Desktop {.unnumbered}
### In console {.unnumbered}
### Amend a previous commit {.unnumbered}
## Pull and push changes up to Github
#### In Rstudio {.unnumbered}
#### In Github Desktop {.unnumbered}
#### Console {.unnumbered}
### I want to pull but I have local work {.unnumbered}
## Merge branch into Main 
### Locally in Github Desktop {.unnumbered}
### In console {.unnumbered}
### In Github: submitting pull requests {.unnumbered}
### Resolving conflicts {.unnumbered}
### Delete your branch {.unnumbered}
#### Github + Rstudio
#### In Github Desktop
### Forking {.unnumbered}
## What we learned
## Git commands {#git}
### Recommended learning {.unnumbered}
### Where to enter commands {.unnumbered}
### Sample commands {.unnumbered}
## Resources

<!--chapter:end:new_pages/collaboration.Rmd-->


# Common errors  

Placeholder


## Interpreting error messages  
## Common errors  
### Typo errors {.unnumbered}  
### Package errors {.unnumbered}  
### Object errors {.unnumbered}  
### Function syntax errors {.unnumbered}
### Logic errors {.unnumbered}  
### Factor errors {.unnumbered}  
### Plotting errors {.unnumbered}  
### R Markdown errors {.unnumbered}  
### Miscellaneous {.unnumbered}  
## Resources { }

<!--chapter:end:new_pages/errors.Rmd-->


# Getting help  

Placeholder


## Github issues  
## Reproducible example  
### The **reprex** package {.unnumbered}  
### Minimal data {.unnumbered}  
## Posting to a forum  
## Resources { }

<!--chapter:end:new_pages/help.Rmd-->


# R on network drives { }  

Placeholder


## Overview {  }
## RStudio as administrator  
## Useful commands 
## Troubleshooting common errors {  }

<!--chapter:end:new_pages/network_drives.Rmd-->


# Data Table { }  

Placeholder


## Intro to data tables {  }
## Load packages and import data { }
### Load packages {.unnumbered}  
### Import data {.unnumbered}
## The i argument: selecting and filtering rows{ }
### Using helper functions for filtering {.unnumbered}  
## The j argument: selecting and computing on columns{ }
### Selecting columns {.unnumbered} 
### Computing on columns {.unnumbered} 
## The by argument: computing by groups{ }
## Adding and updating to data tables { }
## Resources {  }

<!--chapter:end:new_pages/data_table.Rmd-->
