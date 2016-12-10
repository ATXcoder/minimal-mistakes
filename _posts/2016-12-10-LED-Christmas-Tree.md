---
title: LED Christmas Tree
categories: post
tags:
 - DIY
---

Every Christmas I keep telling myself that I am going to add some kind of decoration to my office but never do. Being the 
electronics geek I am though I didn't really want to go out and buy something but instead wanted to build 
something (plus what self respecting maker doesn't like showing off something cool they built).

So while trying thinking about what to build I got a e-mail that the latest version of MagPi Magazine was out for
download and right
there on the front cover was the answer to my question. MagPi had a cool little article about cutting out the front cover,
which was of a Christmas Tree, and replacing the printed lights with real ones that were connected to a RaspberryPi.

My "That is cool and a perfect decoration for my desk at work!" excitement was quickly replaced with the realization that
I don't have a printer (I managed to release the magic smoke from our last one - story for another time) nor do I have a 
RaspberryPi (an issues which is soon to be rectified). 

Determined to do the LED Christmas Tree I realized that I could do the same thing with one of the many 
Arduinos I have laying around and I could build a tree out of lumber I already had laying around (plus I get to 
play with my power tools and do some woodworking which is my 2nd favorite hobby).

<div>
<img style="float:left; margin-right: 10px;" src="https://lh3.googleusercontent.com/sL9HCvnVh0cHJ2tdWM40wZVwG1fguiuThAj19Kazc6cZ6_b8fIAc3Iye0HWS1BO3CHzEfLkyJdC59pzjqA8f-pS9Y7nyeHtNirYkSyz4RZ4A0grSMdgkEKfyiqsLHqf935VGZcsXGpPLtBQFNiXm_zYT5_tCnJ4cH85OfY32BrnV2MHgs5tm6niag4V06i_Ko7zflobBj00Q3qFfS_-NRWkuG-4FpYsEnmCVEGBktUgeyGmZHQ3c9gwYlxVeDl9UGVqrkVsdsb9EXmgGUta4miiPRdeFRs6Oe5xVfOH2elsGZuKUHlVe51UfunL6u-CIq7duaAUXzwwCeT8x8gXT0wBG9KRB-s4PN0T_sem3m4oZQhpjFOFaY4MK9VuvF-XfbmzLjZXAC9Y97V7cJvmCXqHHmGOtUO5TlksqAI93fsSPlLVoedOtnIJMmxTin2NlllRT4Ylf_TjevEhssbk6efe9zV9rQfVQafqpI6GxOm6a4Kwy0RBVyLrms4MNsWV_vxrmC_k6FIVS7SrR1rdVznwCzrox_iieitexOxrQ9zNemc1gzcXXWZb2iTFk0sC-GoEuGuohZAgj7D-0c5fkPb_FpI67OOIGM0TIPa8Cq-Z1fXBKhQ=w479-h638-no" width="200" height="100">

<img style="float:left; margin-right: 10px;" src="https://lh3.googleusercontent.com/CrVZAGyPSNKWFtB4ak2U--vTKHF4Qp4z_zr34y_zZ7Xj3yL0pRVtRUHnk__XKCfInIl7AJyq7-4K1e2iSAcNe4RdLpeeOnUptA8TEv6syzMdjZ2CnV0h9lA5pN5IpsikYfxVZ1W16v0v6ajviCvfVsUg2MgHewFAoxBnUYdzkrxXzGFJPM4ezrW2We3Bt_XSRkBvt8SicHrVrJcrCnZC8Ayd4KD81Et5MftVktRjnCAEPMRqfe-HyVNTDHNy-PQHi-HhLx-7UnoWN8DU0g0-MPp6lO3Q30PXN351Qe_TFmwq0IQxs6cOEDD1Ipi6vdLvhO80cKyfcv7tfk7w5-4BDedMH0mv2d3LgNUl0HSn0ZAgXdfHstHjjxXajeqfhgUOgSWfNBIW-L3N3i1LE4ubBAb46YqTxFQPDWkcf11f2TYvQfY9ypL7-ILWL3e-lX_eZEvVUN1D8aWTxezkLhyA09QnCleg-El4c70vBu4i6vIPlTGtRMtpabHgtLUMwU9fCwfKBpJXPGPD5hpmVX5MXYNlCop_E2S4AHqA5qFBhh8lc5lKymXNdwOf-2oCyw3lH3Mq3mF00BMT6EpFW0-OALqERikWskEAm_ToFYZweEWhwfNgsw=w479-h638-no" width="200" height="100">

<img style="margin-bottom: 10px;" src="https://lh3.googleusercontent.com/AtxaOm8QG9eaSfySuDjA3X7tRHKAz1eo2rz20-IGIMo8vX7o8M3VDyBKynBaSbe-3Gg35cBEicPCBBIWBLfsqDWFF-Ywm1585jH4OSRxrFrzJprrxiYDFS8uFp__gFbDfw3jXzSsAKo6cvsbrQBKTx1VNxWYrmvA3_bMjjMgOmFA2TP90f6MKtDhotIr9IBL3spkdiwA3E6YG7IctX_sEjomaJS_YAkZbaqNfo09jl_sAEImocvRDTADMTf8aF6_q37zAOnYuPn5ExYCBYJQcn-i-Y0cS3ylJ4DihtA4-t06xG5HODu2cJgblnY_-AuehyTCvnI9vJxNB714U26IoiOi3wxkKVw1wHLP4vdTkhmMrXhkAQVLfwytQaZUhwhPcs5C9Io4Zj_sSzdOYW5j9XLV4qBroCbrZqGqF17ueAamz3oh3V_I5OBOMOVqwiyFF10GRp_My8SyafdoOjEb-yP4z1c-CTEtO63KCvOzSERrxX0Ar7xBU-gUgpQqLBBayOYHvwwc9Kd2dtzDDvV6ptd_qcQI4ZuWENtXrGeLQAzKhYe9bxqH5nHzu05j2WgGlBcVEHPKoK-dvnjTRZ4oGxMvHH56RE_7JFdNQgLZ8RK044r4DA=w479-h638-no" width="200" height="100">
</div>

<iframe width="854" height="480" src="https://www.youtube.com/embed/BqGfQyn0ugM" frameborder="0" allowfullscreen></iframe>