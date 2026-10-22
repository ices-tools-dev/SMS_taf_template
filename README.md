# SMS_taf_template

TAF template for the SMS method: the stochastic multispecies model, run with the R package [smsR](https://github.com/nissandjac/smsR).

The example is the 2026 assessment of sandeel (Ammodytes spp.) in divisions 4.b and 4.c, Sandeel Area 1r (central and southern North Sea, Dogger Bank), by HAWG (ADGSandeel). Its input files are in `boot/initial/data/1r`.

- `data.R`: reads the input files with `getDataSMS()` and sets up the model data, with the surveys, effort and reference points.
- `model.R`: runs the assessment with `runAssessment()`, and a retrospective analysis with Mohn's rho.
- `report.R`: plots of the assessment, Mohn's rho and the diagnostics, and the forecast table with `getForecastTable()`.

Copied from the assessment repository ices-taf/2026_san.sa.1r_assessment at commit bc7cf5e.
