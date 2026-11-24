# HGWM — Selected qualitative navigation cases

Anonymous static supplementary material containing three completed paired cases.
Both Full and WMNav succeed in each selected case, and Full has higher SPL.
These post-hoc qualitative examples are not aggregate performance estimates.
The full quantitative evaluation remains in the manuscript.

## Public files

- `index.html`: self-contained page, English by default, with a Chinese language switch, an embedded recorded-trajectory image, and a JSON download button.
- `cases.json`: the same data embedded in the page; three cases, six Full/WMNav runs, original saved poses and recorded distances, and selected component context metrics.
- `qa_report.json`: validation results for the public files.
- `README.md`: this description.

The page has no external scripts, styles, images, analytics, login requirements, or service dependencies. It can be served from any static file host. No publication status or public URL is asserted here.

Trajectory links join saved high-level poses and do not reconstruct primitive motion. The metric distance is sampled at the recorded metric-read stage of each decision cycle. Path length and SPL come from the evaluator records, not from the displayed polyline. No positions or environment geometry were generated.
