# TTT4265 – Designnotat 6: Operasjonsforsterker

Dette repositoriet inneholder alle datafilene og skriptene som ble brukt til å generere
figurene i kapittel *Realisering og test* i **Designnotat 6**.

## Innhold

- `data/` – rå måledata fra Analog Discovery 2 (åpen sløyfe og lukket sløyfe, 
  ulike laster og amplituder).
- `scripts/` – Python-skript for å:
  - laste inn data
  - beregne spenningsforsterkning og THD
  - generere Bode-plott, tidsdomeneplott og FFT-figurer
- `figures/` – eksporterte figurer som brukes direkte i rapporten.
- `waveforms/` – skjermbilder fra WaveForms (oscilloskop og FFT) som viser
  hvordan amplitude og THD ble målt.
