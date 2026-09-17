# TELAR-Kscar-0.002-UNIVERSAL
**DOI 7 Parkfield 3/3 Blind:** https://doi.org/10.5281/zenodo.22808463

FIA 2026 - Constante universal...
# TELAR-Kscar-0.002-UNIVERSAL
FIA 2026 - Constante universal K_scar=0.002 valida de Black-Scholes a sismos

**Constantes:** K_scar=0.002 | C1=1.7276 C2=0.4231246836990873 C3=2.38662 | Factor 47.0 | ratio_f_S=0.9406

## 7 DOIs Zenodo
1. BS-C - sigma 0.580
2. BS-T - t 0.551  
3. SEISMIC-C Tohoku sigma=0.311384 error 0.0
4. SEISMIC-T Tohoku t=0.551
5. SEISMIC-C Sur CA S=-0.65 sigma=0.27828 (UCERF3)
6. SEISMIC-T Sur CA t=141.62a (5.59% correccion sobre 150a)
7. SEISMIC-PARKFIELD blind 3/3 umbral 0.34541 t_TELAR 21.24y - 2.5y 0.364b M3.5 / 5.1y 0.806b M3.6 / 8.7y 1.235b M3.4

## Sismografo TELAR v1.0
USGS Mw -> S = log10(10^(11.8+1.5*Mw))/47.0
sigma_heter = std(CFF)*C1*K_scar
t_TELAR = C2/(S*K_scar*C3)
Deteccion: CFF > sigma_heter = evento

## Viabilidad
BS-C/BS-T viable para senal de volatilidad (TradingView $99/mes). Sismico valida credibilidad para FIA y reaseguro.

Torreon, Coah - FIA 2026
