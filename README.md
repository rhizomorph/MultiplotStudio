Executable found in /bin/MultiplotStudio.zip. Download, extract and double-click MultiplotStudio.jar (Requires Java 8)

# MultiplotStudio

This is a complete replacement for Multiplot, originally implemented as a GenePattern module (now a standalone desktop app). It has been completely rewritten from the ground up. See preview documentation for further description.

Some key improvements/additions vs the original Multiplot:

    Direct reading of GCTs (no need for MultiplotPreprocces).
    Major reduction in memory requirements.
    Save/Load entire workspace.
    Up to 4 plots at once.
    Independently resizable plot windows
    User can specify exact resolution of copied/exported images.
    Export to SVG format for publication quality plots.
    Alternate display formats for fold change values (e.g. as percentages, log2 fc, ±symmetric, etc.)
    New calculations (std dev, variance, delta factor, ANOVA).
    Additional scope options for existing calculations.
    Option to plot rank of a calculated value instead of the value itself.
    Improved GUI - much more efficient use of screen space.
    Multiple data selection modes (elliptical, freehand, polygon).
    Improved tooltips for mouseover of data points.
    Quick search by probeID or gene symbol.
    Create highlights/filters from lists of gene symbols.
    Batch creation of highlights by dragging multiple TXT files (containing probeIDs or gene symbols, 1 per line) onto workspace.
    Add probeID/gene symbol annotations directly to plots (move by drag-n-drop, customize appearance).
    Add fold change guide lines to any plot containing FC or d-factor values.
    On-the-fly calculation distributions making it easier to find appropriate thresholds for filters/highlights.
    Heatmap for selected subset of data points.
    Edit filters/highlight criteria without having to remove/re-add them.
    Clone filters/highlights.
    Per-plot activation of filters/highlights (apply to all plots, or only some).
    Reorder highlights to determine which points appear on top (for highlights that contain overlapping items).
    Advanced shading options for data points - color points according the intensity of some calculation (or by density).

Known Issues:

    Polygon mouse selection acts a little strange at times (temporarily disabled until resolved).
