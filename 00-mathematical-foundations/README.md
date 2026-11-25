# Module 00 — Mathematical foundations

Status: not assessed.

## Diagnostic (solve manually, without AI or calculator first)

1. Solve 3x - 7 = 11.
2. Rearrange P = VI to isolate I, stating the restriction.
3. Simplify (x^2 - 9)/(x - 3), including the domain restriction.
4. Solve 2x^2 - 8 = 0.
5. Convert 30 degrees to radians and give its exact sine.
6. Solve 2^x = 16.
7. Differentiate f(x) = 3x^2 - 4x + 1.
8. Integrate f(x) = 2x over [0,3].
9. Solve x+y=5 and 2x-y=1.
10. A 640 W module is operated at rated power for 2 h. Calculate energy in kWh, stating the simplifying assumption.

Record reasoning and confidence for each question in the [diagnostic notebook](diagnostic.ipynb). Open it in local JupyterLab, edit the answer cells, save, and submit the notebook or commit for tutor review. Do not mark complete until reviewed.

## First applied case (after diagnostic)

Model the ideal DC output of a synthetic PV string of 26 modules, each rated 640 W. Derive the power formula, convert units, distinguish power from energy, and explain why the STC rating does not predict real annual yield. Extend to solar position and irradiance using pvlib after reviewing trigonometry.

Use public or synthetic data; no employer project information.

### Code development workspace

[Open the Jupyter Notebook](case_001_pv_string.ipynb) | [Open in Google Colab](https://colab.research.google.com/github/Mr-1308/applied-energy-engineering/blob/main/00-mathematical-foundations/case_001_pv_string.ipynb)

Complete the mathematical derivation first, then write your own Python code in the TODO cells. Validate the results against manual calculations, perform sensitivity analysis and develop the PVlib extension after reviewing trigonometry.

To retain your work, save the edited notebook back to the repository (in Colab, File > Save a copy in GitHub, subject to authorization), or commit it locally. Do not mark the exercise completed until reviewed.
