# 施醫信錄：逐面轉錄與捐款名錄

Shi yi xin lu [Report of the Peking Hospital]

版本0.1.0。[倉庫](https://github.com/poplolioi11/bodleian-sinica1630-shiyi-xinlu-1870)及[發行頁](https://github.com/poplolioi11/bodleian-sinica1630-shiyi-xinlu-1870/releases/tag/v0.1.0)為本版預定位置；製備時尚未取得DOI。

《施醫信錄》（Shi yi xin lu）由德貞（John Dudgeon）著校，1870年在北京美華活字書館刊印，牛津博德利圖書館藏本為Sinica 1630。這份倫敦傳道會北京施醫院報告回顧1861至1869年的院務，並討論求診病症、醫學教育、慈善救濟、纏足、麻藥和血液循環知識，末附中外捐款者與銀數，可供晚清醫學史、傳教史、慈善史與翻譯史研究。本版提供20個館方影像幀中32個內容面的AI輔助初錄，以JSON、TXT及TEI保存來源面次與文字單位，另附捐款表、疑讀與小字接續定位；不包含館方影像。疑讀已標記，尚未經人類全文校勘或專家審定，方法與限制另見說明。

Shi yi xin lu (Report of the Peking Hospital), prepared by John Dudgeon and printed at the American Mission Press in Peking in 1870, is held as Bodleian Sinica 1630. This London Missionary Society hospital report reviews its work from 1861 to 1869, discussing patient conditions, medical teaching, charitable care, footbinding, anaesthetics and knowledge of circulation; it also lists Chinese and foreign contributors and recorded silver amounts. The dataset supports histories of medicine, missions, philanthropy and translation through an AI-assisted initial transcription of 32 content faces within 20 official image canvases, including Chinese and English title pages. JSON, TXT and TEI preserve source-face and text-unit references, accompanied by a literal donor table, uncertainty records and small-note continuation links. Source images are excluded. Uncertain readings are marked; the text has not undergone full human collation or expert approval.

固定20個館方影像幀中的32個內容面、407個來源文字單位，保留134筆疑讀與22個未解字形標記。[book.json](book.json)為分層文字資料，[book.txt](book.txt)與[book.tei.xml](book.tei.xml)逐單位保留相同字串；它們沒有提供逐字字框。

[DONORS.csv](DONORS.csv)有53個原文表格欄目，含群體及機構署名；銀數保持原字與原單位，沒有換算或重算總額。[12個小註接續](READING-MAP.json)須連到各自主欄／表格欄目閱讀，不能把TXT列序直接當成連續正文。原印合計保留為原書文字，沒有代作者核算。

[原件](https://digital.bodleian.ox.ac.uk/objects/b5eb81ca-42ca-49c9-9372-aac27572a35e/)、[IIIF清單](https://iiif.bodleian.ox.ac.uk/iiif/manifest/b5eb81ca-42ca-49c9-9372-aac27572a35e.json)、[館目固定快照](https://github.com/bodleian/east-asian-mss/blob/c177d5a6db8585168b744d38a6bff02186d1968f/collections/chinese/Sinica%201630.xml)；[來源](PROVENANCE.md)、[讀者指南](READING-GUIDE.md)、[疑讀](uncertainties.json)、[品質](QUALITY.md)、[方法](METHODS.md)、[權利](RIGHTS.md)。

整理者曲宸宇／Chu, Chen-Yu（帳號poplolioi11），[ORCID](https://orcid.org/0009-0003-9738-6914)。歷史作者與資料整理者分開；無館方背書。
