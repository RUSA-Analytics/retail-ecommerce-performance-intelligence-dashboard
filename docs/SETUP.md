# Setup and Publication Notes

## To open the Power BI project

1. Install a current version of Microsoft Power BI Desktop.
2. Download the `.pbix` file when it is added to the repository.
3. Keep the accompanying dataset in the documented relative location.
4. Open the report and refresh the model.
5. Confirm that all visuals load without missing-field or relationship errors.

## Mandatory QA before adding the `.pbix`

- Sort month names chronologically using a month-number field.
- Reconcile every narrative insight with the visual and filtered values.
- Correct the new-customer percentage so it matches the underlying counts.
- Validate geography figures against the corresponding charts.
- Confirm that drill-through pages respect the selected context.
- Verify that Bottom 10 visuals use the correct ascending logic.
- Remove any unsupported performance, adoption, savings, or business-impact claims.
- Test every slicer, tooltip, bookmark, button, and page navigation action.
- Remove personal paths, credentials, gateway references, and confidential metadata.

## Recommended public-release contents

- `README.md`
- Screenshots in `assets/`
- Documentation in `docs/`
- Sanitized `.pbix` file
- Synthetic or anonymized sample dataset
- Data dictionary and measure catalogue

Do not upload raw client data, credentials, access tokens, or confidential business information.

