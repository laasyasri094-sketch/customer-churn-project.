{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Bold;\f1\froman\fcharset0 Times-Roman;\f2\fmodern\fcharset0 Courier;
}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa321\partightenfactor0

\f0\b\fs48 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Customer Churn Prediction and Analysis\
\pard\pardeftab720\sa298\partightenfactor0

\fs36 \cf0 Project overview\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Analyzed a sample telecom customer dataset to understand churn patterns, identify higher-risk customer groups, and build a baseline churn prediction model.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 What I did\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0
\f1\b0\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Cleaned the data with Python, including converting 
\f2\fs26 TotalCharges
\f1\fs24  to numeric and filling 11 blank values for customers with zero tenure.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Used exploratory analysis and SQL to compare churn across customer and service groups.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Built a logistic regression model and evaluated it on a held-out test set.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Created an interactive dashboard in Looker Studio.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Findings\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0
\f1\b0\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Overall churn in the dataset was 
\f0\b 26.54%
\f1\b0 .\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Month-to-month customers had a 
\f0\b 42.71%
\f1\b0  churn rate; two-year customers had a 
\f0\b 2.83%
\f1\b0  churn rate.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Churned customers had a median tenure of 
\f0\b 10 months
\f1\b0 , compared with 
\f0\b 38 months
\f1\b0  for customers who stayed.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The model\'92s ROC-AUC was 
\f0\b 0.842
\f1\b0 .\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 At a 0.40 prediction threshold, it flagged 440 test customers: 250 churners were correctly flagged, while 190 flagged customers stayed.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Recommendation\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 A retention team could test earlier outreach for newer, month-to-month customers. These results show patterns in this dataset; they do not prove what caused churn or that an intervention will reduce it.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \
}