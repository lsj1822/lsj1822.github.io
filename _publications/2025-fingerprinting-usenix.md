---
title: "[Poster] Fingerprinting QUIC browser clients"
collection: publications
category: posters
permalink: /publication/fingerprinting-poster
excerpt: 'Different QUIC browser clients can be fingerprinted by a passive adversary.'
date: 2025-08-13
venue: 'USENIX Security'
authors: 
  - name: 'Seungju Lee'
    style: 'bold_underline'
---

Authors: **Seungju Lee**

[Abstract]<br>
As it is encrypted by default, QUIC is advertised as a privacy-first alternative to the traditional TCP + TLS network stack. But how much does QUIC protect our privacy in real life? We are interested in how much information QUIC leaks about clients in practice. In this work we evaluate the fingerprintability of popular QUIC browser clients by a passive observer using interoperability with different server implementations, connection IDs, and transport parameters. We find that all three methods leak information about the browser client in a easily identifiable manner.