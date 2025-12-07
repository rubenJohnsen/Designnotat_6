# TTT4265 – Designnotat 6: Operasjonsforsterker

Dette repositoriet inneholder alle datafilene og skriptene som ble brukt til å generere
figurene i kapittel *Realisering og test* i **Designnotat 6**.

## Innhold

- `data/` – rå måledata fra Analog Discovery 2 (åpen sløyfe og lukket sløyfe, 
  ulike laster og amplituder).
- `scripts/` – Python/MATLAB-skript for å:
  - laste inn data
  - beregne spenningsforsterkning og THD (jf. ligningene \eqref{eq:forsterkning}–\eqref{eq:THD} i notatet)
  - generere Bode-plott, tidsdomeneplott og FFT-figurer
- `figures/` – eksporterte figurer som brukes direkte i rapporten.
