# airline_satisfaction

## Tableau Dashboard [here](https://public.tableau.com/app/profile/bara.samudra.syuhada/viz/P0M1_bara/Dashboard1?publish=yes)

# **English**

## Repository Outline

`This section briefly describes the contents of the files pushed to the repository.`

```
1. P0M1_bara.ipynb - Notebook containing the introduction, problem statement, data loading, data cleaning, analysis, and visualization using Python, leading up to final conclusions
2. P0M1_bara_dataset.csv - Raw dataset used for data processing
3. P0M1_bara_clean_dataset.csv - Cleaned dataset
4. P0M1_bara.twb - Tableau data visualization project file

```

## Problem Background

```
I am a Data Analyst working within the flight coordination division for Airline X. This division acts as a flight coordinator, connecting all ground units to ensure flights depart on time and assisting with flight plan preparations, including flight routes. The marketing division recently conducted a passenger satisfaction survey. They want to understand why a majority of customers expressed dissatisfaction with Airline X and aim to improve customer satisfaction rates. Consequently, they have requested data analysts across various divisions—including flight coordination—to process the survey data and extract analytical insights to help identify the key factors influencing customer satisfaction.

```

## Project Output

```
The output of this project consists of 4 data visualizations, 1 descriptive statistical analysis, and 1 inferential statistical analysis derived from the dataset to address the problem statement along with the final conclusions.

```

## Data

```
The dataset used was published on Kaggle by Arseniy Shutko. It contains anonymous survey results conducted by an airline regarding passenger satisfaction.

Dataset Link: 
https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k

The dataset consists of 129,880 rows and 22 columns with the following schema:

Passenger Information:
Gender: gender of the passenger (Male/Female) 
Customer Type: customer loyalty status (Loyal/Disloyal) 
Age: age of the passenger (numerical) 
Type of Travel: purpose of travel (Personal/Business) 
Class: travel class (Business/Eco/Eco Plus) 
Flight Distance: flight distance in miles (numerical)

Service Quality Ratings (1-5 scale) or 0 (0 = unrated):
Inflight wifi service: satisfaction with inflight Wi-Fi 
Departure/Arrival time convenient: satisfaction with departure/arrival times 
Ease of Online Booking: satisfaction with the online booking process 
Gate location: satisfaction with gate locations 
Food and drink: satisfaction with food and drinks provided by the airline 
Online boarding: satisfaction with online check-in 
Seat comfort: satisfaction with seat comfort 
Inflight entertainment: satisfaction with inflight entertainment options 
On-board service: satisfaction with cabin crew service 
Leg room service: satisfaction with legroom space 
Baggage handling: satisfaction with baggage handling 
Checkin service: satisfaction with check-in service 
Cleanliness: satisfaction with cabin cleanliness 

Delay Times:
Departure Delay in Minutes: departure delay duration 
Arrival Delay in Minutes: arrival delay duration 

Customer Satisfaction:
Satisfaction: True = satisfied, False = dissatisfied

```

## Method

```
This project utilizes descriptive statistics (measures of central tendency, data dispersion, and distributions) as well as inferential statistics (Two-Sample Independent T-Test).

```

## Tech Stack

```
Programming Language: Python
Python Libraries:
- pandas
- matplotlib
- scipy
Other Tools: Tableau (Data Visualization)
This section outlines the tech stack used, including programming languages, tools, and Python libraries.

```

## References

`Data Reference: [https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k](https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k)`

Tableau Public URL (Data Visualization):
[https://public.tableau.com/app/profile/bara.samudra.syuhada/viz/P0M1_bara/Dashboard1?publish=yes](https://public.tableau.com/app/profile/bara.samudra.syuhada/viz/P0M1_bara/Dashboard1?publish=yes)


# **Indonesia**

## Repository Outline
`Bagian ini menjelaskan secara singkat konten/isi dari file yang dipush ke repository`


```
1. P0M1_bara.ipynb - Notebook yang berisi perkenalan, problem statement data loading, data cleaning analisis dan visualisasi data dengan python, hingga kesimpulan akhir
2. P0M1_bara_dataset.csv - Dataset mentah yang digunakan untuk pengolahan data
3. P0M1_bara_clean_dataset.csv - Dataset yang telah dilakukan cleaning
4. P0M1_bara.twb - File proyek visualisasi data Tableau
```

## Problem Background
```
Saya merupakan seorang Data Analyst yang bekerja di bawah divisi *flight coordination* untuk maskapai X. Divisi ini berperan sebagai koordinator penerbangan seperti menghubungkan seluruh unit di darat agar jadwal penerbangan tepat waktu dan membantu persiapan rencana terbang termasuk jalur penerbangan. Divisi pemasaran baru-baru ini melakukan survey kepuasan penumpang dengan penerbangan mereka. Mereka ingin mengethaui kenapa lebih banyak pelanggan yang tidak puas dengan maskapai X dan ingin meningkatkan satisfaction rate pelanggan. Selanjutnya mereka menginginkan data analyst dari berbagai divisi, termasuk divisi *flight coordination* untuk mengolah data survey tersebut dan memberikan insight dari hasil analisis sebagai bahan pertimbangan mereka untuk mencari tahu lebih lanjut terkait faktor apa yang paling berperan terhadap kepuasan pelanggan.
```

## Project Output
```
Output projek ini ialah 4 buah visualisasi data, 1 buah analisis statistika deskriptif, dan 1 buah analisis statistika inferensial dari data yang ada untuk menjawab penjabaran dari problem statement yang ada beserta kesimpulannya.
```

## Data
```
Dataset yang digunakan di publish di Kaggle oleh Arseniy Shutko. Data tersebut merupakan hasil survey anonim yang dilakukan oleh suatu maskapai penerbangan terhadap kepuasan para penumpang maskapai tersebut.

Berikut link dataset yang digunakan: 
https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k

Adapun dataset terdiri atas 129880 baris dan 22 kolom dengan nama kolom sebagai berikut:

Informasi Penumpang:
Gender: jenis kelamin penumpang (Male/Female) 
Customer Type: tipe penumpang (Loyal/Disloyal) 
Age: usia penumpang (numerical) 
Type of Travel: tujuan berpergian (Personal/Business) 
Class: kelas penerbangan (Business/Eco/Eco Plus) 
Flight Distance: jarak penerbangan dalam mil (numerical)

Rating kualitas layanan (1-5) atau 0 (0 = tidak memberi rating)
Inflight wifi service: kepuasan dengan wifi di pesawat 
Departure/Arrival time convenient: kepuasaan dengan waktu keberangkatan/kedatangan 
Ease of Online Booking: kepuasan dengan proses booking online 
Gate location: kepuasan dengan lokasi gate 
Food and drink: kepuasan dengan makanan dan minuman yang disediakan maskapai 
Online boarding: kepuasan dengan online check-in 
Seat comfort: kepuasan dengan kenyamanan seat penumpang 
Inflight entertainment: kepuasan dengan pilihan hiburan dalam pesawat 
On-board service: kepuasan dengan pelayanan saat penerbangan 
Leg room service: kepuasan dengan layanan legroom 
Baggage handling: kepuasan dengan penanganan bagasi
Checkin service: kepuasan dengan layanan check-in 
Cleanliness: kepuasan dengan kebersihan kabin 

Waktu delay:
Departure Delay in Minutes: delay keberangkatan 
Arrival Delay in Minutes: delay kedatangan 

Kepuasan Pelanggan
Satisfaction: True = puas, False = tidak puas
```

## Method
```
Pada project ini terdapat metode statistika deskriptif (central tendency, sebaran data, dan distribusi) serta statistika inferensial (Two Sample Independent Test) yang digunakan
```

## Stacks
```
Bahasa pemrograman: Python
Library python:
- pandas
- matplotlib
- scipy
Tools lain: Tableau (Visualisasi Data)
Bagian ini menjelaskan stacks yang digunakan seperti bahasa pemrograman, tools, dan library Python yang digunakan`
```

## Reference
`Referensi Data: https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k`

URL Tableau Public (Visualisasi Data):
https://public.tableau.com/app/profile/bara.samudra.syuhada/viz/P0M1_bara/Dashboard1?publish=yes

---