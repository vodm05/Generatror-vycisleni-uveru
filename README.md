# Generatror-vycisleni-uveru

Tento kód slouží pro účely vyčíslení úvěru k určitému datu. Proces je nastavený tak, že uživatel nahraje splátkový kalendář, zadá období počtu měsíců k předčasnému splacení úvěru a navazující období počtu měsíců k předčasnému splacení, vybere datum, ke kterému chce vytvořit vyčíslení a vybere z nabídky společnost, které se týká vyčíslení (na základě výběru se doplňují údaje do samotného dokumentu, jako je hlavička, číslo smlouvy atd.).

Výstupem je word dokument připravený k podepsání, vzor je v repozitáři.

Za účelem ochrany údajů klienta a samotné společnosti není uveden kód s částí API, která by jinak stahovala z interní databáze klienty a jejich informace. Je pouze odkazováno na excel soubor s těmito informacemi za účelem fungování kódu. Avšak opět z důvodu ochrany, není tento soubor nahrán.
