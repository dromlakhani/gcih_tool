# Glucocorticoid-induced Hyperglycemia (GCIH) Management Tool

## Overview

This web-based tool is designed to assist healthcare providers in managing Glucocorticoid-induced Hyperglycemia (GCIH) in hospitalized patients. It provides personalized recommendations for insulin regimens based on patient characteristics and the administered glucocorticoid.

The tool is based on the research and recommendations from the following paper:

Lakhani OJ, Kumar S, Tripathi S, Desai M, Seth C. Comparison of two protocols in the management of glucocorticoid-induced hyperglycemia among hospitalized patients. Indian J Endocr Metab 2017;21:836-44.

## Features

- Input patient data (weight, glucocorticoid type and dose, diabetes status, HbA1c)
- Calculate appropriate correctional insulin dose
- Recommend insulin type based on the administered glucocorticoid
- Provide additional recommendations for background insulin in patients with pre-existing diabetes
- Generate easy-to-read recommendations for GCIH management

## How to Use

1. Download the HTML file (`gcih_management_tool.html`) from this repository.
2. Open the file in a web browser (Chrome, Firefox, Safari, or Edge).
3. Fill in the patient details in the form:
   - Patient weight (kg)
   - Glucocorticoid type (prednisolone, methylprednisolone, dexamethasone, or hydrocortisone)
   - Glucocorticoid dose (mg)
   - Diabetes status (no pre-existing diabetes or known diabetes)
   - HbA1c (%) for patients with known diabetes
4. Click the "Generate Recommendation" button.
5. View the personalized GCIH management recommendation displayed below the form.

## Technical Details

- The tool is implemented as a single HTML file with embedded JavaScript.
- Styling is done using Tailwind CSS (loaded via CDN).
- No server-side processing is required; all calculations are performed client-side.

## Disclaimer

This tool is intended to be used by healthcare professionals as a guide only. It does not replace clinical judgment. Always consider individual patient factors and consult appropriate guidelines and specialists when making treatment decisions.

## Citation

If you use or reference this tool in your work, please cite the original paper:

Lakhani OJ, Kumar S, Tripathi S, Desai M, Seth C. Comparison of two protocols in the management of glucocorticoid-induced hyperglycemia among hospitalized patients. Indian J Endocr Metab 2017;21:836-44.

DOI: 10.4103/ijem.IJEM_226_17

## License

This tool is provided under the MIT License. See the LICENSE file for more details.

## Contributing

Contributions to improve the tool are welcome. Please submit issues or pull requests through the project's GitHub repository.
