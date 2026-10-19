# Eshop-Sales-Excel-Dashboard
Excel dashboard o predaji e-shopu pre category managera a riaditeľa. 
Dáta boli spracované v Exceli pomocou kontingenčných tabuliek, slicerov a kontingenčných grafov.
This Excel dashboard covers e-shop sales for a category manager and a company director. 
The data was processed in Excel using pivot tables, slicers and pivot charts.
#  Project Title / Headline
Jednalo sa o projekt analýzy predaja e-shopu za obdobie január 2024 až máj 2026. V rámci projektu bolo hlavnou úlohou pripraviť podklady pre category managera, ktorý rozhoduje o sortimente a marži, a zjednodušený prehľad pre riaditeľa.
The project concerned the analysis of e-shop sales from January 2024 to May 2026. The main task was to prepare background materials for a category manager, who makes decisions about the product range and margins, and a simplified overview for the director.
# Short Description / Purpose
Na základe dát o objednávkach bolo treba pripraviť analýzu zameranú na jednotlivé oblasti:

1.Aký je vývoj tržieb, zisku a marže v čase (roky, mesiace).
2.Ktoré kategórie, regióny, kanály a segmenty (B2B / B2C) tvoria najväčší podiel na tržbách a zisku.
3.Ktoré produkty sú najdôležitejšie (Top 10 podľa tržieb a zisku).
4.Ktoré produkty patria do tried A, B a C podľa ABC analýzy.
5.Kde sú produkty s vysokými tržbami, ale nízkou maržou.

Based on order data, an analysis needed to be prepared focusing on the following areas:

1.How do revenue, profit and margin develop over time (years, months)?
2.Which categories, regions, channels and segments (B2B / B2C) generate the largest share of revenue and profit?
3.Which products matter most (Top 10 by revenue and profit)?
4.Which products belong to classes A, B and C according to ABC analysis?
5.Where are the products with high revenue but low margin?
# Tech Stack

Dashboard bol vytvorený pomocou nasledujúcich nástrojov:

📊 Excel – kontingenčné tabuľky a kontingenčné grafy
🎛️ Slicery a Timeline – interaktívne filtre (rok, mesiac, región, kategória, segment)
🧮 Vzorce – výpočet kumulatívneho podielu a triedy A / B / C 
📁 File Format – .xlsx (dva súbory: verzia pre category managera a pre riaditeľa)
The dashboard was created using the following tools:

📊 Excel – pivot tables and pivot charts
🎛️ Slicers and Timeline – interactive filters (year, month, region, category, segment)
🧮 Formulas – calculation of cumulative share and class A / B / C
📁 File Format – .xlsx (two files: category manager version and director version)
# Data Source

Dáta obsahovali 500 objednávok a 32 produktov za obdobie od 1. 1. 2024 do 30. 5. 2026. Dáta boli doplnené o ABC kategóriu na základe tržieb a zisku.

Dáta obsahovali:

dátum a číslo objednávky
zákazníka a segment (B2B / B2C)
región, štát a predajný kanál (E-shop, Prodejna, Velkoobchod)
kategóriu a produkt
množstvo, jednotkovú cenu a zľavu
tržbu, náklad, zisk a maržu

The data contained 500 orders and 32 products from 1 January 2024 to 30 May 2026.The data were supplemented with an ABC category based on revenue and profit.

The data included:

order date and order number
customer and segment (B2B / B2C)
region, country and sales channel (E-shop, Prodejna, Velkoobchod)
category and product
quantity, unit price and discount
revenue, cost, profit and margin

# Features / Highlights

Vymedzenie problému:

Category manager potrebuje rýchlo vidieť, ktoré produkty a kategórie prinášajú tržby a zisk a kde je marža nízka. Bez prehľadu v jednom súbore bolo potrebné ručne filtrovať surové dáta.

Cieľom dashboardu:

Poskytnúť category managerovi podklady pre rozhodovanie o sortimente.
Porovnať tržby a zisk podľa kategórií, regiónov, kanálov a segmentov.
Identifikovať najdôležitejšie produkty pomocou ABC analýzy podľa tržieb aj podľa zisku.
Ukázať vývoj tržieb, zisku a marže po rokoch a mesiacoch.
Pripraviť pre riaditeľa zjednodušený prehľad hlavných ukazovateľov.
Kľúčové vizualizácie:

1.KPI cards: tržby, zisk, náklady, marža %
2.Filtre: rok, mesiac, región, kategória, segment
3.Graf Top 10 produktov: súčet tržieb a zisku
4.ABC analýza podľa tržieb a podľa zisku (hranice 80 % a 95 % kumulatívneho podielu)
5.Vývoj tržieb, zisku a marže po rokoch a mesiacoch
6.Podiel tržieb podľa segmentu, kategórie a kanála

Kľúčové zistenia:

1.Celkové tržby 4,23 mil. Kč, zisk 1,23 mil. Kč, marža 29,1 %.
2.Elektronika tvorí 49,5 % tržieb, ale má najnižšiu maržu (24,8 %). Sport má najvyššiu maržu (36,7 %).
3.Notebook 14" tvorí 33 % všetkých tržieb, ale len 28 % zisku.
4.ABC analýza: 9 produktov (trieda A) tvorí cca 79 % tržieb, 13 produktov (trieda C) len cca 5 %.
5.Triedy A / B / C sa podľa tržieb a podľa zisku líšia (napr. Toner HP 12A, Reproduktor BT).
6.Údaje za rok 2026 sú len do mája, preto je potrebné porovnávať rovnaké obdobia.

Problem Definition:

A category manager needs to quickly see which products and categories bring revenue and profit and where the margin is low. Without an overview in one file, raw data had to be filtered manually.

Dashboard Objectives:

Provide the category manager with background materials for product range decisions.
Compare revenue and profit by category, region, channel and segment.
Identify the most important products using ABC analysis by revenue and by profit.
Show the development of revenue, profit and margin by year and month.
Prepare a simplified overview of the main indicators for the director.

Key visualizations:

1.KPI cards: revenue, profit, costs, margin %
2.Filters: year, month, region, category, segment
3.Top 10 products chart: total revenue and profit
4.ABC analysis by revenue and by profit (thresholds at 80 % and 95 % cumulative share)
5.Development of revenue, profit and margin by year and month
6.Share of revenue by segment, category and channel

Key findings:

1.Total revenue CZK 4.23 million, profit CZK 1.23 million, margin 29.1 %.
2.Electronics account for 49.5 % of revenue but have the lowest margin (24.8 %). Sport has the highest margin (36.7 %).
3.Notebook 14" generates 33 % of total revenue but only 28 % of profit.
4.ABC analysis: 9 products (class A) generate about 79 % of revenue, while 13 products (class C) generate only about 5 %.
5.Classes A / B / C differ by revenue and by profit (e.g. Toner HP 12A, Reproduktor BT).
6.Data for 2026 runs only until May, so like-for-like periods must be compared.

## 6. Screenshots 

<img width="1416" height="995" alt="Dashoard-sales-report-director" src="https://github.com/user-attachments/assets/37fb8182-9f7b-4c67-82e2-c3b8dc325770" />
<img width="1920" height="1080" alt="Dashboard-predaj-kanal" src="https://github.com/user-attachments/assets/b77b3eb8-5c17-494f-a852-7482138acc6f" />
<img width="1920" height="1080" alt="prehlad-predaj-region" src="https://github.com/user-attachments/assets/292ba6fa-0780-48c9-b240-cf0b86e7c7e8" />
<img width="1920" height="1080" alt="prehlad-predaj-produkty" src="https://github.com/user-attachments/assets/a0ef3350-aa7b-49d3-96c9-60702f911505" />
<img width="1920" height="1080" alt="prehlad-predaja-kategorie" src="https://github.com/user-attachments/assets/c9b07152-0e59-4b88-b1bf-c68ff13c662f" />





