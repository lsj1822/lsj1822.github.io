---
title: "QUICstep: Evaluating connection migration based QUIC censorship circumvention"
collection: publications
category: conferences
permalink: /publication/quicstep-pets
excerpt: 'Connection migration can be used to circumvent QUIC SNI censorship in a lightweight, effective, and efficient manner.'
award: 'Andreas Pfitzmann Best Paper Award'
awardurl: 'https://www.petsymposium.org/student-paper-award.php'
date: 2026-07-20
venue: 'PETS'
authors: 
  - name: 'Seungju Lee'
    style: 'bold_underline'
  - name: 'Mona Wang'
  - name: 'Watson Jia'
  - name: 'Qiang Wu'
  - name: 'Henry Birge-Lee'
  - name: 'Liang Wang'
  - name: 'Prateek Mittal'
paperurl: '../files/quicstep-pets.pdf'
---
[Download paper](../../files/quicstep-pets.pdf)

Authors: **Seungju Lee**, Mona Wang, Watson Jia, Qiang Wu, Henry Birge-Lee, Liang Wang, Prateek Mittal

[Abstract]<br>
Internet censors often rely on information in the first few packets of a connection to censor unwanted traffic. With the rise of the QUIC transport protocol, prior work has suggested the method of using QUIC connection migration to conceal the first few handshake packets using a different network path (e.g., an encrypted proxy channel). However, the use of connection migration for censorship circumvention has not been explored or validated in terms of feasibility or performance. We bridge this gap by providing a rigorous quantitative evaluation of this approach that we name QUICstep. We develop a lightweight, application-agnostic prototype of QUICstep and demonstrate that QUICstep is able to circumvent a real-world QUIC SNI censor. We find that not only does QUICstep outperform a fully encrypted channel in diverse settings, but also that it can significantly reduce traffic load for encrypted channel providers. We also propose using QUICstep as a tool for measuring QUIC connection migration support in the wild and show that support for connection migration is on the rise. While as of now QUIC and connection migration support is limited, we envision that QUICstep can be a useful tool for the future where QUIC is the de facto norm for the Internet.