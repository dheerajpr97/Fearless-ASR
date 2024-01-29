Project: From SAD to ASR on the Fearless Steps Data
===================================================

Overview
--------

This project focuses on developing an autonomous speech recognition system using the Fearless Steps - 02 (FS-02) Corpus from NASA's Apollo missions. The system comprises three main sub-tasks: Speaker Activity Detection (SAD), Speaker Identity Detection (SID), and Automatic Speech Recognition (ASR).

Objectives
----------

*   **SAD**: Differentiate tangible speech from non-speech in audio, achieving a DCF of 2.44% on the FS-02 Development dataset.
*   **SID**: Identify speakers from voice attributes, reaching a Top-5 Accuracy of 91.65% and an overall Accuracy of 76.89%.
*   **ASR**: Incorporate speaker identification into an end-to-end speech recognition system, achieving a WER of 32.9% with the Baseline Transformer model.

Integration
-----------

*   **Speaker Diarization (SD)**: Combined temporal information from SAD with speaker predictions from SID, achieving a DER of 56.78%.
*   **Enhanced ASR**: Improved ASR with SAD information, reaching a WER of 59.4%.

Technologies Used
-----------------

*   Neural Networks: ResNet, LSTM, Transformer Model
*   Clustering Algorithms: DBSCAN, Mean Shift
*   Evaluation Metrics: DCF, WER, DER

Acknowledgments
-----------------
We express our sincere gratitude to the Fearless Steps initiative by the University of Texas at Dallas and NASA for providing the FS-02 Corpus. Special thanks to the mentors and colleagues at the Universität Paderborn (Fachgebiet Nachrichtentechnik) for their invaluable guidance and support throughout this project. We also acknowledge the contributions of the research community, whose insights and feedback have been instrumental in the development of this work.
