# SMS Spam Detection: TF-IDF vs Sentence-BERT

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/H7modi77/Project-NLP/blob/main/Notebook/SMS_Spam_Detection_Group9.ipynb)

ARTI 404 - Natural Language Processing (Section 7MA2) - Group 9
Imam Abdulrahman Bin Faisal University
Instructor: Dr. Mohammed Mosuily

| Name | Student ID |
|---|---|
| Mohammed Nasser Almarhoon (team leader) | 2240005893 |
| Ali Zuhair Alsaffar | 2240005706 |

## Files

| Folder | Files |
|---|---|
| `Report/` | `Report_Group9.pdf`, `Report_Group9.docx` - project report (seven sections) |
| `Presentation/` | `Presentation_Group9.pdf`, `Presentation_Group9.pptx` - presentation slides |
| `Appendix/` | `Appendix_Group9.pdf` - team details, contributions and skills |
| `Notebook/` | `SMS_Spam_Detection_Group9.ipynb` - notebook with outputs: Setup, Data, Method 1, Method 2, Results, Try it, Sources |
| `Data/` | `SMSSpamCollection.tsv` - the real dataset used in the project |
| `Test/` | `test_sms.csv` - SMS messages for testing the models (message, expected label, type) |

## Dataset

**UCI SMS Spam Collection** - 5,574 English SMS messages (4,827 ham, 747 spam). Each line is `label<TAB>message`.

- Original source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection
- License: CC BY 4.0
- T. A. Almeida, J. M. G. Hidalgo, and A. Yamakami, "Contributions to the study of SMS spam filtering: new collection and results," Proc. DocEng, 2011.

## How to run

Open the notebook in Google Colab and choose *Runtime → Run all*. It downloads the dataset from UCI; if `data/SMSSpamCollection.tsv` is next to the notebook, that copy is used instead. To try the models, type a message in the *Try it* cell; `Test/test_sms.csv` has ready examples.
