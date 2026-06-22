# Analyza_vyvoje_mezd
Analýza vývoje mezd v ČR v letech 2011 - 2024 (Python + Power BI)

Tento projekt se zabývá analýzou českých mzdových dat scrapenutých z ISPV.cz pomocí Pythonu a vizualizací klíčových zjištění v Power BI.  
Cílem je porozumět vývoji mezd v ČR, regionálním rozdílům, vlivu vzdělání, věku a dlouhodobým trendům.


## Přehled projektu

Projekt je rozdělen do dvou částí:

### **1) Zpracování a analýza dat (Python)**
- scrapenutí dat z webu ispv.cz
- čištění a příprava datových sad  
- spojování dat podle věku, vzdělání a regionu  
- agregace a výpočet popisných statistik  
- export očištěných dat do Excelu  

### **2) Interaktivní dashboard (Power BI)**
- úvodní přehled hlavních zjištění
- regionální porovnání mezd  
- segmentace podle věku, vzdělání a pohlaví 
- vlastní vizuály a jednotný design dashboardu  


## Struktura repozitáře

- data_vek/               # data podle věkových skupin
- data_vzdelani/          # data podle vzdělání
- inflace_2000_2025/      # data o inflaci
- Projekt.ipynb           # Jupyter Notebook s analýzou
- vizualizace.pbix        # Power BI dashboard

## Použité technologie

- **Python** (pandas, numpy, matplotlib, seaborn)  
- **Jupyter Notebook**  
- **Power BI Desktop**  
- **Excel**  
- **Git & GitHub**

## Hlavní zjištění (příklady)

- Celkový růst mezd mezi lety 2011 a 2024 byl 87,99 %, ale reálný růst (po očištění o inflaci) pouze 17,71 %
- Největší rozpětí mezd je ve věkové skupině 60 let a více
- Největší rozdíl mezi mzdovou a platovou sférou je u vysokoškolsky vzdělaných pracovníků
- Gender gap je patrná napříč všemi skupinami, nejvíce se projevuje ve věkových kategoriích 30 - 39 let a 40 - 49 let

## Ukázky vizuálu + datový model
<img width="1452" height="852" alt="image" src="https://github.com/user-attachments/assets/8757d7a1-ea43-4c05-ac9b-0188ce2f6c06" />
<img width="1462" height="852" alt="image" src="https://github.com/user-attachments/assets/b2e4d7db-0581-471f-9236-0feb925ef66a" />
<img width="1457" height="851" alt="image" src="https://github.com/user-attachments/assets/d60438ff-d92a-47b3-8acc-96ba11c4a16b" />
<img width="1452" height="840" alt="image" src="https://github.com/user-attachments/assets/e756fc12-16da-4229-812a-64e47290b0ed" />
<img width="1452" height="845" alt="image" src="https://github.com/user-attachments/assets/7c180f83-320d-4adc-895a-31c821fc2735" />
<img width="1282" height="726" alt="image" src="https://github.com/user-attachments/assets/2ef14734-1a26-446c-8734-0c0e30229768" />

## Autor

Marie Pojarová
