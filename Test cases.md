## ﻿**Test Case ID**: TC01

**Test Title**: Verify that User can insert a certificate that is older than 100 years

**Precondition**: The User must be registered on the MatchIT app

|Step|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to MatchIT app||User is in MatchIT app|
|2|Click on “Profil” ||User is on “Profil” page|
|3|Click on “Sertifikati”||User is on “Sertifikati” page|
|4|Click on “Dodaj sertifikat”||User is on “Dodaj sertifikat” page|
|5|Write in “Naziv sertifikata” field|“HTML”|The provided data is visible in the “Naziv sertifikata” field|
|6|Write in “Nosilac sertifikata” field|“HTMLschool”|The provided data is visible in the “Nosilac sertifikata” field|
|7|Click and pick date|“1900”|Picked date is visible|
|8|Click on “Sačuvaj”||The certificate is added and visible|
<br>
<br>

## ﻿**Test Case ID**: TC02

**Test Title**: Verify that User cannot select more than 20 years of experience  in the “Tehnologije” page

**Precondition**: The User must be registered on the MatchIT app. The User must have at least one technology selected in the “Tehnologije” page with 20 years of experience.

|Step|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to MatchIT app||User is in MatchIT app|
|2|Click on “Profil” ||User is on “Profil” page|
|3|Click on “Iskustvo”||User is on “Iskustvo” page|
|4|Choose one technology in which the user has 20 years of experience and click one time on plus button||By clicking the plus button, the user does not increase years of experience. The years remain the same|
<br>
<br>

## ﻿**Test Case ID**: TC03

**Test Title**: Verify that number cannot be in the “Prezime” field

**Description**: Verify that Surname can not contains numbers

**Precondition**: The User must be registered on the MatchIT app. The User must have a name and surname in the “Osnovni podaci” page.

|Step|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to MatchIT app||User is in MatchIT app|
|2|Click on “Profil” ||User is on “Profil” page|
|3|Click on “Osnovni podaci”||User is on “Osnovni podaci” page and name and surname are displayed|
|4|Click on “Prezime” i write number|“2”|An error message appears “Surname cannot contain numbers”|
<br>
<br>

## ﻿**Test Case ID**: TC04

**Test Title**: Verify that HR can place a salary with range from 0 to 1 euro in new “Dodaj oglas” ad

**Precondition**: The HR must be registered on the MatchIT web page. 

|Step|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to MatchIT web page|“https://company.matchit.rs/job-offers”|All existing ads are visible on the page|
|2|Click on “Dodaj oglas”||“Dodaj oglas” page is opened|
|3|Fill in all mandatory fields||All mandatory fields are filled with correct data|
|4|Fill in “Neto plata u €”|In min “0” and in max “1”|The provided data is visible in the “Neto plata u €” fields|
|5|Click on “Kreiraj” button||The ad is created and page is back on “Svi oglasi” page|
