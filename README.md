# True-Detective
Disguised Face Recognition w.r.t CCTV View

For FYP-2021-TrueDetective17Batch

True Detective is an intelligent system that recognizes a person from a cctv point of view. The person may disguise themselves using face mask, fake beard, hasts, glasses or just their bare face.

## Brief Description

1. **TrueDetective** is an intelligent system that identifies a person through their face.
2. The face of the person may be bare or disguised.
3. There are 4 disguises in the dataset: face mask, glasses, fake beard, hats.
4. The recognition is performed on CCTV images and videos.
5. The data is self-collected images from CCTV viewpoints. (Full info in the `datasetinfo` file.)

## Code

The `DisguisedTrueDetective_1.py` file contains the entire code for disguise face recognition on CCTV images. You need to upload it to Colab and convert it into an `.ipynb` notebook and run it (due to the large file size, it was uploaded with a `.py` extension).

## Dataset

**Dataset Used:** TrueDetectiveDataset-1


It contains pictures of 11 different individuals each comprisig of atleast 250 pictures. The train and test data are disjoint. Download The dataset via the link provided and use the password given for it.

**Disguised Appearances Include:**
- Bare Face Images
- Glasses
- Hats
- Fake Beard
- Face Masks

**Image Variations:**
- Various backgrounds
- Complex and simple backgrounds
- Side views
- Light and dark conditions
- Occlusion
- CCTV view

With respect to fyp-1, we did recognition on BareFace, Glasses and Hat Recognition. With respect to fyp-2 we did recognition on Fake Baerd, Face Mask. The Test Train Data distribution is as below.

## INFO

- **Total Size:** 10.08 GB
- **Password for Dataset:** `#FYP17Trudetective1!`
- [Download Dataset](https://drive.google.com/drive/folders/1Yo1DerbK6ziiCmWEPTX7wViSQbCywfQX?usp=sharing)
  

**IMAGES:** [BARE FACE, GLASSES, HATS, FAKE BEARD, FACE MASK]  
**Total Individuals:** 11  
**Total Images:** 2201

## Distribution

### P1 - LAIBA
- Bare Face: 51
- Glasses: 35
- Hats: 44
- Fake Beard: 45
- Face Mask: 38
- **Total Images:** 213

### P2 - RUHMA
- Bare Face: 36
- Glasses: 32
- Hats: 27
- Fake Beard: 34
- Face Mask: 31
- **Total Images:** 160

### P3 - ABDUL SAAD
- Bare Face: 61
- Glasses: 42
- Hats: 31
- Fake Beard: 38
- Face Mask: 45
- **Total Images:** 217

### P4 - ABDUR RAFAY
- Bare Face: 39
- Glasses: 71
- Hats: 89
- Fake Beard: 46
- Face Mask: 62
- **Total Images:** 307

### P5 - HURAIRA
- Bare Face: 90
- Glasses: 53
- Hats: 51
- Fake Beard: 40
- Face Mask: 48
- **Total Images:** 282

### P6 - HASSAN
- Bare Face: 21
- Glasses: 32
- Hats: 27
- Fake Beard: 45
- Face Mask: 38
- **Total Images:** 162

### P7 - ZARYAB
- Bare Face: 21
- Glasses: 45
- Hats: 26
- Fake Beard: 32
- Face Mask: 53
- **Total Images:** 177

### P8 - IBRAHIM
- Bare Face: 19
- Glasses: 87
- Hats: 40
- Fake Beard: 31
- Face Mask: 24
- **Total Images:** 201

### P9 - ANAS
- Bare Face: 18
- Glasses: 09
- Hats: 20
- Fake Beard: 48
- Face Mask: 39
- **Total Images:** 134

### P10 - MUSAAB
- Bare Face: 28
- Glasses: 23
- Hats: 25
- Fake Beard: 48
- Face Mask: 26
- **Total Images:** 150

### P11 - MUNZAR
- Bare Face: 45
- Glasses: 41
- Hats: 43
- Fake Beard: 44
- Face Mask: 25
- **Total Images:** 198


## Train Set

- **P1**  
  - Bare Face: 19  
  - Glasses: 17  
  - Hats: 17  
  - Fake Beard: 18  
  - Face Mask: 17  
  - **Sub-Total:** 88

- **P2**  
  - Bare Face: 15  
  - Glasses: 12  
  - Hats: 11  
  - Fake Beard: 15  
  - Face Mask: 15  
  - **Sub-Total:** 68

- **P3**  
  - Bare Face: 20  
  - Glasses: 12  
  - Hats: 11  
  - Fake Beard: 17  
  - Face Mask: 19  
  - **Sub-Total:** 79

- **P4**  
  - Bare Face: 15  
  - Glasses: 18  
  - Hats: 27  
  - Fake Beard: 16  
  - Face Mask: 27  
  - **Sub-Total:** 103

- **P5**  
  - Bare Face: 14  
  - Glasses: 14  
  - Hats: 14  
  - Fake Beard: 18  
  - Face Mask: 21  
  - **Sub-Total:** 81

- **P6**  
  - Bare Face: 10  
  - Glasses: 12  
  - Hats: 14  
  - Fake Beard: 18  
  - Face Mask: 16  
  - **Sub-Total:** 70

- **P7**  
  - Bare Face: 09  
  - Glasses: 12  
  - Hats: 08  
  - Fake Beard: 10  
  - Face Mask: 22  
  - **Sub-Total:** 61

- **P8**  
  - Bare Face: 09  
  - Glasses: 21  
  - Hats: 10  
  - Fake Beard: 14  
  - Face Mask: 11  
  - **Sub-Total:** 65

- **P9**  
  - Bare Face: 08  
  - Glasses: 05  
  - Hats: 07  
  - Fake Beard: 21  
  - Face Mask: 17  
  - **Sub-Total:** 58

- **P10**  
  - Bare Face: 12  
  - Glasses: 09  
  - Hats: 06  
  - Fake Beard: 22  
  - Face Mask: 11  
  - **Sub-Total:** 60

- **P11**  
  - Bare Face: 19  
  - Glasses: 15  
  - Hats: 17  
  - Fake Beard: 18  
  - Face Mask: 11  
  - **Sub-Total:** 80

**Total Images in Train Set:** 774

## Test Set

- **P1**  
  - Bare Face: 32  
  - Glasses: 18  
  - Hats: 27  
  - Fake Beard: 27  
  - Face Mask: 21  
  - **Sub-Total:** 125

- **P2**  
  - Bare Face: 21  
  - Glasses: 20  
  - Hats: 16  
  - Fake Beard: 19  
  - Face Mask: 16  
  - **Sub-Total:** 92

- **P3**  
  - Bare Face: 41  
  - Glasses: 30  
  - Hats: 20  
  - Fake Beard: 21  
  - Face Mask: 26  
  - **Sub-Total:** 138

- **P4**  
  - Bare Face: 24  
  - Glasses: 53  
  - Hats: 62  
  - Fake Beard: 30  
  - Face Mask: 35  
  - **Sub-Total:** 204

- **P5**  
  - Bare Face: 76  
  - Glasses: 39  
  - Hats: 37  
  - Fake Beard: 22  
  - Face Mask: 27  
  - **Sub-Total:** 152

- **P6**  
  - Bare Face: 11  
  - Glasses: 19  
  - Hats: 13  
  - Fake Beard: 27  
  - Face Mask: 22  
  - **Sub-Total:** 92

- **P7**  
  - Bare Face: 12  
  - Glasses: 12  
  - Hats: 18  
  - Fake Beard: 22  
  - Face Mask: 18  
  - **Sub-Total:** 82

- **P8**  
  - Bare Face: 10  
  - Glasses: 21  
  - Hats: 14  
  - Fake Beard: 17  
  - Face Mask: 13  
  - **Sub-Total:** 75

- **P9**  
  - Bare Face: 10  
  - Glasses: 04  
  - Hats: 13  
  - Fake Beard: 27  
  - Face Mask: 21  
  - **Sub-Total:** 75

- **P10**  
  - Bare Face: 16  
  - Glasses: 14  
  - Hats: 19  
  - Fake Beard: 26  
  - Face Mask: 15  
  - **Sub-Total:** 90

- **P11**  
  - Bare Face: 26  
  - Glasses: 26  
  - Hats: 26  
  - Fake Beard: 26  
  - Face Mask: 14  
  - **Sub-Total:** 118

**Total Images in Test Set:** 1,046

TRAIN SET:

P1 BARE FACE= 19 , GLASSES= 17 ,HATS= 17, FAKEBEARD= 18, FACEMASK= 17 [Sub-Total = 88] P2 BARE FACE= 15 , GLASSES= 12 ,HATS= 11, FAKEBEARD= 15, FACEMASK= 15 [Sub-Total = 68] P3 BARE FACE= 20 , GLASSES= 12 ,HATS= 11, FAKEBEARD= 17, FACEMASK= 19 [Sub-Total = 79] P4 BARE FACE= 15 , GLASSES= 18 ,HATS= 27, FAKEBEARD= 16, FACEMASK= 27 [Sub-Total = 103] P5 BARE FACE= 14 , GLASSES= 14 ,HATS= 14, FAKEBEARD= 18, FACEMASK= 21 [Sub-Total = 42] P6 BARE FACE= 10 , GLASSES= 12 ,HATS= 14, FAKEBEARD= 18, FACEMASK= 16 [Sub-Total = 70] P7 BARE FACE= 09 , GLASSES= 12 ,HATS= 08, FAKEBEARD= 10, FACEMASK= 22 [Sub-Total = 61] P8 BARE FACE= 09 , GLASSES= 21 ,HATS= 10, FAKEBEARD= 14, FACEMASK= 11 [Sub-Total = 65] P9 BARE FACE= 08 , GLASSES= 05 ,HATS= 07, FAKEBEARD= 21, FACEMASK= 17 [Sub-Total = 58] P10 BARE FACE= 12 , GLASSES= 09 ,HATS= 06, FAKEBEARD= 22, FACEMASK= 11 [Sub-Total = 60] P11 BARE FACE= 19 , GLASSES= 15 ,HATS= 17, FAKEBEARD= 18, FACEMASK= 11 [Sub-Total = 80]

		Total Images in Train Set = [774]
TEST SET:

P1 BARE FACE= 32, GLASSES= 18 ,HATS= 27, FAKEBEARD=27 , FACEMASK= 21 [Sub-Total = 125] P2 BARE FACE= 21 , GLASSES= 20 ,HATS= 16, FAKEBEARD=19 , FACEMASK= 16 [Sub-Total = 92] P3 BARE FACE= 41 , GLASSES= 30 ,HATS= 20, FAKEBEARD=21 , FACEMASK= 26 [Sub-Total = 138] P4 BARE FACE= 24 , GLASSES= 53 ,HATS= 62, FAKEBEARD=30 , FACEMASK= 35 [Sub-Total = 204] P5 BARE FACE= 76 , GLASSES= 39 ,HATS= 37, FAKEBEARD=22 , FACEMASK= 27 [Sub-Total = 152] P6 BARE FACE= 11 , GLASSES= 19 ,HATS= 13, FAKEBEARD=27 , FACEMASK= 22 [Sub-Total = 92] P7 BARE FACE= 12 , GLASSES= 33 ,HATS= 18, FAKEBEARD=19 , FACEMASK= 31 [Sub-Total = 113] P8 BARE FACE= 10 , GLASSES= 66 ,HATS= 30, FAKEBEARD=17 , FACEMASK= 14 [Sub-Total = 137] P9 BARE FACE= 10 , GLASSES= 04 ,HATS= 13, FAKEBEARD= 27, FACEMASK= 22 [Sub-Total = 76] P10 BARE FACE= 16 , GLASSES= 14 ,HATS= 19, FAKEBEARD= 26, FACEMASK= 15 [Sub-Total = 90] P11 BARE FACE= 26 , GLASSES= 26 ,HATS= 26, FAKEBEARD= 26, FACEMASK= 14 [Sub-Total = 118]

		Total Images in Train Set = [1337]
