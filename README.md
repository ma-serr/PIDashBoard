# Serrano Lab PI Progress Dashboard

A streamlined, interactive web dashboard for Principal Investigators (PIs) to **track trainee progress** in research, professional development, and compliance using CSV exports from the Serrano Lab Training Matrix.


## Features

- **Drag-and-drop CSV upload**: Import trainee progress data directly.
- **Interactive filtering**: Filter by trainee level or skill area.
- **Progress visualization**: Summary cards, area heatmaps, and individual progress bars.
- **Export options**: Download group CSV or PDF for reporting.
- **Responsive, accessible, and mobile-friendly**.
- **No back-end required**: All processing is in-browser for maximum data privacy.



## Usage

1. **Export** individual trainee CSVs from the Training Matrix tool.
2. **Open** `OnBoardingHTML.html` in your browser (recommended: Chrome or Firefox).
3. **Drag and drop** or **click to upload** trainee CSVs.
4. **Filter** and **review** progress using the dashboard controls.
5. **Export** aggregated progress data as CSV or PDF for reports.

> **Note:** For data privacy, all computation and rendering is client-side; no data is sent to a server.


## File Structure

- `OnBoardingHTML.html` — Main dashboard HTML (open this to use the dashboard).
- `logo.png` — Lab logo for branding (can be replaced with your own).
- `*.csv` — Trainee progress CSV files (exported from Training Matrix).
- `README.md` — This documentation file.



## Dependencies

- [Google Fonts: Inter](https://fonts.google.com/specimen/Inter)
- [Chart.js](https://www.chartjs.org/) (loaded via CDN for future data viz extensions)
- No build tools required; everything runs in-browser.



## Customization

- **Branding**: Replace `logo.png` with your own lab or institutional logo.
- **Styling**: Modify colors and layout in the `<style>` block in `OnBoardingHTML.html`.
- **SVG Icons**: You may customize dashboard icons (see included SVGs).



## Citation & Credits

This dashboard is developed and maintained by the **Serrano Lab** at Boston University Center for Regenerative Medicine (CReM).

If you use or modify this dashboard, **please cite**:

> Serrano Lab PI Progress Dashboard, Center for Regenerative Medicine (CReM), Boston University, 2025.  
> https://serranolab.org  
>  
> Portions of this code adapted from open-source projects, including [Chart.js](https://www.chartjs.org/).

**If you use or adapt this dashboard in your own lab, please add a citation or link to this repository or website.**

---

## License

MIT License (see [LICENSE](LICENSE) for details).  
Feel free to use, modify, and extend for non-commercial research purposes.

---

## Contact

For questions or suggestions, please contact **Angie Serrano**  
[serranolab.org](https://serranolab.github.io/online/) | Boston University CReM  
📧 [maserr@bu.edu](mailto:maserr@bu.edu)



