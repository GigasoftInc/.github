# Gigasoft, Inc. — ProEssentials Charting SDK

**The World's Fastest .NET WPF, WinForms, and MFC C++ Charting Components.**
GPU compute shader accelerated. AI-assisted development. Intelligent rendering. Mission-critical quality since 1993.

---

## Why ProEssentials?

Founded in 1993, Gigasoft has concentrated exclusively on charting for over 30 years — scientific, engineering, and financial data visualization at a mission-critical level. Prioritizing stability, speed, and rendering intelligence. Fast expert support. No hassle evaluation download.

ProEssentials is architecturally different from every competitor — a native Win32 DLL charting engine with two complete API layers: a hierarchical .NET property interface for WPF and WinForms, and a standard C/C++ DLL API for MFC, Delphi, ActiveX, and any language with DLL FFI capability. Both APIs access the same rendering engine, the same GPU compute shaders, and the same 1,200+ chart properties.

---

## AI-Assisted Development — pe_query.py

ProEssentials v10 includes a purpose-built AI Code Assistant that transforms how you implement charts. The **pe_query.py** tool gives AI assistants on-demand access to the complete ProEssentials API — 1,200+ properties, 167 enumerations, and 116 working code examples — with a built-in validation layer that cross-checks every property path against DLL ground truth, eliminating the hallucinated code that plagues generic AI coding.

Works with Claude, ChatGPT, Gemini, GitHub Copilot, and Cursor. Included free with every ProEssentials v10 license.

➡️ [Explore the AI Code Assistant](https://gigasoft.com/ai-code-assistant)

---

## Five Chart Objects. One SDK.

| Object | Best For |
|--------|----------|
| **Pego** | Bar, line, area, OHLC — dashboards, financial charts |
| **Pesgo** | Scientific XY scatter, real-time streaming, irregular time-series |
| **Pe3do** | 3D surface, wireframe, contour |
| **Pepso** | Polar, Smith chart, radar/spider |
| **Pepco** | Pie charts |

---

## Platform Coverage — One Product, Eight Targets

| Platform | Supported |
|----------|-----------|
| WPF (.NET 8 / .NET 6 / .NET 4.8) | ✅ Native WPF controls |
| WinForms (.NET 8 / .NET 6 / .NET 4.8) | ✅ Native WinForms controls |
| C++ MFC / Win32 | ✅ Native DLL API |
| Delphi VCL | ✅ Native DLL API |
| ActiveX / COM / Access / Excel | ✅ OCX controls |
| ASP.NET Web Forms | ✅ |
| LabVIEW | ✅ via ActiveX |
| Any language with DLL FFI | ✅ Standard Win32 DLL |

➡️ [Full Platform Coverage Comparison](https://gigasoft.com/why-proessentials/platform-coverage)

---

## Licensing — Perpetual. No Subscriptions. No Surprises.

ProEssentials is the only WPF charting library with a true perpetual license. Pay once. Use forever. Free unlimited support for life. Royalty-free deployment to unlimited end-user machines. No annual renewal. No subscription expiry traps. No reactivation fees.

➡️ [Pricing & Support Comparison vs SciChart, LightningChart, Syncfusion, DevExpress](https://gigasoft.com/why-proessentials/pricing-support)

---

## Get Started

| Resource | Link |
|----------|------|
| ⬇️ No-hassle evaluation download | [Download](https://gigasoft.com/net-chart-component-wpf-winforms-download) |
| 📖 Developer Guide | [gigasoft.com/developer-guide](https://gigasoft.com/developer-guide) |
| 🚀 WPF .NET 8 Walk-Through | [gigasoft.com/wpf-chart-nuget](https://gigasoft.com/wpf-chart-nuget) |
| 🚀 WinForms .NET 8 Walk-Through | [gigasoft.com/net-chart-nuget](https://gigasoft.com/net-chart-nuget) |
| 🔍 API Explorer | [gigasoft.com/documentation](https://gigasoft.com/documentation) |
| 💬 Contact & Support | [gigasoft.com/contact](https://gigasoft.com/contact) |

---

## Demo Gallery — Browse by Use Case

Every demo is a GPU-accelerated ProEssentials v10 chart sample for C# on .NET 8. Most ship for **both WPF and WinForms** — pick your platform from the links beside each preview.


### Real-Time & High-Performance Charts

GPU compute shader rendering of millions to hundreds of millions of points per update — real-time streaming, oscilloscope, and live data charts for C# .NET applications.

| Preview | Demo |
| --- | --- |
| <a href="https://github.com/GigasoftInc/wpf-chart-fast-100m-points-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-fast-100m-points-proessentials/main/docs/GigaPrime2D-100MPoints-Wpf.png" width="300" alt="wpf-chart-fast-100m-points-proessentials"></a> | **100 Million Points — Fastest Demo**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-fast-100m-points-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-100million-points-proessentials)<br><br>.NET 8 — a demonstration of GPU compute shader rendering: 100 million data points completely re-passed and re-rendered per timer tick. Live FPS displayed in the title bar. |
| <a href="https://github.com/GigasoftInc/wpf-realtime-circular-buffer-8million-points-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-realtime-circular-buffer-8million-points-proessentials/main/docs/screen146.png" width="300" alt="wpf-realtime-circular-buffer-8million-points-proessentials"></a> | **Real-Time Circular Buffer — 8M Points, Zero-Copy**<br>[WPF](https://github.com/GigasoftInc/wpf-realtime-circular-buffer-8million-points-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-realtime-circularbuffer-computeshader-direct3d-proessentials)<br><br>.NET 8 — 4 subsets × 2,000,000 points streamed in real time via zero-copy `UseDataAtLocation` + `CircularBuffers` + Direct3D ComputeShader. A timer appends 150 samples/subset every 15ms; a right-click submenu toggles Stationary vs Scrolling zoom. |
| <a href="https://github.com/GigasoftInc/wpf-3d-surface-realtime-computeshader-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-3d-surface-realtime-computeshader-proessentials/main/docs/Wpf-RealTime-Surface-GigaSoft-413.png" width="300" alt="wpf-3d-surface-realtime-computeshader-proessentials"></a> | **Real-Time 3D Surface — Compute Shader**<br>[WPF](https://github.com/GigasoftInc/wpf-3d-surface-realtime-computeshader-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-3d-surface-realtime-computeshader-circularbuffer-proessentials)<br><br>.NET 8 — the fastest possible realtime 3D surface update: 720,000 vertices rebuilt every 15 ms using GPU compute shaders and a zero-copy circular-buffer append strategy. A single `Pe3do` 3D chart, Direct2D. |
| <a href="https://github.com/GigasoftInc/wpf-heatmap-realtime-spectrogram-computeshader-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-heatmap-realtime-spectrogram-computeshader-proessentials/main/docs/wpf-heatmap-spectrogram-gigasoft-139.png" width="300" alt="wpf-heatmap-realtime-spectrogram-computeshader-proessentials"></a> | **Real-Time Spectrogram Heatmap**<br>[WPF](https://github.com/GigasoftInc/wpf-heatmap-realtime-spectrogram-computeshader-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-heatmap-realtime-spectogram-computeshader-proessentials)<br><br>.NET 8 — a realtime heatmap/spectrogram that replaces the entire 93,696-value surface every 25ms using a tiled data pool + `Array.Copy` + zero-copy `UseDataAtLocation`, GPU ComputeShader. Direct3D. |

### 3D Surface & Terrain Charts

GPU-accelerated 3D surface, height-map, point cloud, and Delaunay triangulation charts for scientific, engineering, and terrain visualization in WPF and WinForms.

| Preview | Demo |
| --- | --- |
| <a href="https://github.com/GigasoftInc/wpf-chart-3d-surface-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-3d-surface-proessentials/main/docs/GigaPrime3D-WpfSurfaceChart.jpg" width="300" alt="wpf-chart-3d-surface-proessentials"></a> | **3D Surface Height Map (flagship 3D/2D demo)**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-3d-surface-proessentials)<br><br>Likely the most impressive functioning, performing, efficient 3D/2D combo example you will find on GitHub. A .NET 8 demonstration of GPU compute shader 3D surface rendering — real material surface and terrain height-map data visualized across three synchronized charts. |
| <a href="https://github.com/GigasoftInc/wpf-3d-lidar-point-cloud-computeshader-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-3d-lidar-point-cloud-computeshader-proessentials/main/docs/Gigasoft-Lidar-Wpf-Chart-2M-points.png" width="300" alt="wpf-3d-lidar-point-cloud-computeshader-proessentials"></a> | **3D LiDAR Point Cloud — 2.5M Returns**<br>[WPF](https://github.com/GigasoftInc/wpf-3d-lidar-point-cloud-computeshader-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-3d-lidar-point-cloud-computeshader-proessentials)<br><br>.NET 8 demonstration of the v10.0.0.24 ComputeShader path for `PolyMode = Scatter` — rendering 2.5M Mt. Tamalpais LiDAR returns as a 3D scatter cloud with every point individually colored by elevation. |
| <a href="https://github.com/GigasoftInc/wpf-chart-3d-delaunay-triangulation-surface-heightmap-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-3d-delaunay-triangulation-surface-heightmap-proessentials/main/docs/screen414.png" width="300" alt="wpf-chart-3d-delaunay-triangulation-surface-heightmap-proessentials"></a> | **3D Delaunay Triangulation Surface**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-3d-delaunay-triangulation-surface-heightmap-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-3d-delaunay-triangulation-surface-heightmap-proessentials)<br><br>.NET 8 — a `Pe3do` Delaunay-triangulated 3D surface with contour coloring, built from 70 scattered XYZ sound-meter readings. Direct3D. |
| <a href="https://github.com/GigasoftInc/wpf-chart-delaunay-triangulation-2d-contour-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-delaunay-triangulation-2d-contour-proessentials/main/docs/screen147.png" width="300" alt="wpf-chart-delaunay-triangulation-2d-contour-proessentials"></a> | **Delaunay Triangulation 2D Contour**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-delaunay-triangulation-2d-contour-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-delaunay-triangulation-2d-contour-proessentials)<br><br>.NET 8 — a `Pesgo` continuous Delaunay contour fill (`SGraphPlottingMethod.ContourDelaunay`) from 70 scattered XYZ sound-meter readings, with a custom tooltip and a title-bar interpolated-Z readout. Direct3D composite. |

### Oil & Gas / Geophysical & Well Log Charts

Well log, cement bond log (VDL), ultrasonic borehole imaging, wellbore trajectory, and NEXRAD radar charts for oil & gas, geophysical, and GIS software.

| Preview | Demo |
| --- | --- |
| <a href="https://github.com/GigasoftInc/wpf-3d-surface-wellbore-flythrough-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-3d-surface-wellbore-flythrough-proessentials/main/docs/screen403.png" width="300" alt="wpf-3d-surface-wellbore-flythrough-proessentials"></a> | **3D Wellbore Flythrough (Oil & Gas GIS)**<br>[WPF](https://github.com/GigasoftInc/wpf-3d-surface-wellbore-flythrough-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-3d-surface-wellbore-oil-gas-gis-proessentials)<br><br>.NET 8 — a complete 3D subsurface visualization with an animated roller-coaster style camera flythrough down multiple wellbore trajectories, using a single `Pe3do` Direct3D chart object. |
| <a href="https://github.com/GigasoftInc/wpf-chart-vdl-wireline-acoustic-cement-bond-log-heatmap-contour"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-vdl-wireline-acoustic-cement-bond-log-heatmap-contour/main/docs/wpf-winforms-chart-vdl-wireline-rectilinear-heatmap-contour-direct3d.png" width="300" alt="wpf-chart-vdl-wireline-acoustic-cement-bond-log-heatmap-contour"></a> | **VDL Wireline Acoustic — Cement Bond Log**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-vdl-wireline-acoustic-cement-bond-log-heatmap-contour) · [WinForms](https://github.com/GigasoftInc/Winforms-chart-vdl-wireline-rectlinear-heatmap-contour-cement-bond-log)<br><br>.NET 8 — a wireline Variable Density Log (VDL) acoustic visualization for cement bond evaluation. Time on X (~200–1200 µs), depth on Y (feet), color = waveform amplitude, rendered with a contour-with-injection technique that keeps cells crisp at scale. Direct3D + GPU compute shader, custom 8-stop blue ramp. |
| <a href="https://github.com/GigasoftInc/wpf-chart-ultrasonic-borehole-image-dual-contour-heatmap"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-ultrasonic-borehole-image-dual-contour-heatmap/main/docs/gigasoft-demo-wireline-awcn-ttcn.png" width="300" alt="wpf-chart-ultrasonic-borehole-image-dual-contour-heatmap"></a> | **Ultrasonic Borehole Image — Dual Contour**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-ultrasonic-borehole-image-dual-contour-heatmap) · [WinForms](https://github.com/GigasoftInc/winforms-chart-ultrasonic-borehole-image-dual-contour-heatmap)<br><br>.NET 8 — dual-channel ultrasonic borehole image (AWCN amplitude + TTCN transit time) rendered as a single concatenated contour chart sharing one colormap, one zoom, one rendering pass. A top-right overlay button toggles null rendering (Black / Gaps). Direct3D + GPU compute shader. |
| <a href="https://github.com/GigasoftInc/wpf-chart-nexrad-radar-reflectivity-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-nexrad-radar-reflectivity-proessentials/main/docs/Wpf-NexRad-2D-Contour-Gigasoft-120.png" width="300" alt="wpf-chart-nexrad-radar-reflectivity-proessentials"></a> | **NEXRAD Doppler Radar Reflectivity**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-nexrad-radar-reflectivity-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-nexrad-radar-proessentials)<br><br>.NET 8 — real NEXRAD Level II radar data from KFWS (Dallas/Fort Worth) rendered as an 800×450 2D contour chart with the official NWS standard reflectivity color table, a geographic map background, and a custom XYZ tooltip. Direct3D + ComputeShader. |

### Heatmap & 2D Contour Charts

GPU-rendered 2D contour and heatmap charts with color-mapped surfaces — spectrograms, frequency analysis, and intensity maps for scientific data.

| Preview | Demo |
| --- | --- |
| <a href="https://github.com/GigasoftInc/wpf-heatmap-2d-contour-spectrogram-frequency-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-heatmap-2d-contour-spectrogram-frequency-proessentials/main/docs/wpf-heatmap-spectrogram-gigasoft-139.png" width="300" alt="wpf-heatmap-2d-contour-spectrogram-frequency-proessentials"></a> | **2D Spectrogram Heatmap (frequency)**<br>[WPF](https://github.com/GigasoftInc/wpf-heatmap-2d-contour-spectrogram-frequency-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-heatmap-2d-contour-spectogram-frequency-proessentials)<br><br>.NET 8 — a full-featured heatmap / spectrogram / 2D contour visualization (frequency vs time vs amplitude) using `Pesgo` with `ContourColors`, log Y axis, and GPU ComputeShader. Direct3D. |

### Financial & Signal-Processing Charts

OHLC candlestick, technical indicator, trading signal, and audio waveform oscilloscope charts for financial and signal-processing applications.

| Preview | Demo |
| --- | --- |
| <a href="https://github.com/GigasoftInc/wpf-chart-financial-ohlc-trading-signals-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-financial-ohlc-trading-signals-proessentials/main/docs/screen030.png" width="300" alt="wpf-chart-financial-ohlc-trading-signals-proessentials"></a> | **Financial OHLC + Trading Signals**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-financial-ohlc-trading-signals-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-financial-ohlc-trading-signals-studies-proessentials)<br><br>.NET 8 — a complete financial charting app built on `Pego` (the categorical / date-axis graph object): OHLC candlesticks for ten real stock symbols with Bollinger Bands, RSI, a custom stochastic oscillator, and Buy/Sell signal annotations generated from stochastic turning points. Direct2D, four synchronized multi-axes. |
| <a href="https://github.com/GigasoftInc/wpf-audio-waveform-oscilloscope-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-audio-waveform-oscilloscope-proessentials/main/docs/Wpf-Audio-Oscilloscope-Chart-ProEssentials.png" width="300" alt="wpf-audio-waveform-oscilloscope-proessentials"></a> | **Audio Waveform Oscilloscope**<br>[WPF](https://github.com/GigasoftInc/wpf-audio-waveform-oscilloscope-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-audio-viewer-oscilloscope-proessentials)<br><br>.NET 8 — dual-channel audio oscilloscope with a 5-song playlist, MCI playback, real-time playhead, O-Scope/dBFS/Lyrics/Overlap modes, synchronized lyrics overlay, and a full right-click custom menu. |

### Techniques & How-To Examples

Focused C# how-to examples — multi-axis layouts, custom axis labels, log-log scales, mouse interaction and hot spots, bitmap symbols, and a clone-build-run quickstart.

| Preview | Demo |
| --- | --- |
| <a href="https://github.com/GigasoftInc/wpf-chart-quickstart-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-quickstart-proessentials/main/docs/screen100.png" width="300" alt="wpf-chart-quickstart-proessentials"></a> | **Quickstart — Clone, Build, Run**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-quickstart-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-quickstart-proessentials)<br><br>.NET 8 — the simplest starting point: a single `Pesgo` scientific chart (Example 100, *Simple Scientific Graph*) plotting four subsets of random performance data with gradient + bevel plotting, dot grid, zoom/pan, and a tracking tooltip. Direct2D. |
| <a href="https://github.com/GigasoftInc/wpf-chart-multi-axis-layout-explorer-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-multi-axis-layout-explorer-proessentials/main/docs/WpfChartMultiAxisLayoutExplorer.png" width="300" alt="wpf-chart-multi-axis-layout-explorer-proessentials"></a> | **Multi-Axis Layout Explorer**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-multi-axis-layout-explorer-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-multi-axes-tutorial-proessentials)<br><br>.NET 8 — a single `Pesgo` scientific chart displaying engine dyno data (HP, Torque, Temperature, Pressure vs RPM) across four instantly switchable axis layout modes, with a toggle that moves Pressure to the right Y axis in whichever layout is active. Mixed plotting methods per subset (Bar, SplineArea, PointsPlusLine, Spline). Direct2D. |
| <a href="https://github.com/GigasoftInc/wpf-chart-mouse-interaction-hotspots-coordinate-tracking-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-mouse-interaction-hotspots-coordinate-tracking-proessentials/main/docs/WpfChartMouseInteractionHotspots.png" width="300" alt="wpf-chart-mouse-interaction-hotspots-coordinate-tracking-proessentials"></a> | **Mouse Interaction & Hot Spots**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-mouse-interaction-hotspots-coordinate-tracking-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-mouse-interaction-hotspots-proessentials)<br><br>.NET 8 — a dual-Y-axis `Pego` chart that combines two complementary mouse-interaction techniques: a `ConvPixelToGraph` tooltip showing both Y-axis values at the cursor, and a `GetHotSpot` status bar that names the chart element under the cursor (data point, series legend, or point label). Direct2D. |
| <a href="https://github.com/GigasoftInc/wpf-chart-custom-yaxis-labels-annotations-events-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-custom-yaxis-labels-annotations-events-proessentials/main/docs/WpfChartCustomScales.png" width="300" alt="wpf-chart-custom-yaxis-labels-annotations-events-proessentials"></a> | **Custom Y-Axis Labels & Annotations**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-custom-yaxis-labels-annotations-events-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-custom-axis-labels-proessentials)<br><br>.NET 8 — two approaches to custom Y-axis labels shown side-by-side in one chart split into stacked multi-axis sections. Direct2D. |
| <a href="https://github.com/GigasoftInc/wpf-chart-log-log-axes-drag-measure-quick-annotations-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-log-log-axes-drag-measure-quick-annotations-proessentials/main/docs/WpfChartLogLogDragMeasure.png" width="300" alt="wpf-chart-log-log-axes-drag-measure-quick-annotations-proessentials"></a> | **Log-Log Axes + Drag-Measure Annotations**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-log-log-axes-drag-measure-quick-annotations-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-log-log-axes-quick-annotations-proessentials)<br><br>.NET 8 — log-log scientific scatter chart with intelligent decade-based axis restructuring on zoom, plus a left-drag quick annotation measurement tool that overlays a live measurement rectangle with X/Y delta labels. Direct2D. |
| <a href="https://github.com/GigasoftInc/wpf-chart-bitmap-symbols-jagged-data-proessentials"><img src="https://raw.githubusercontent.com/GigasoftInc/wpf-chart-bitmap-symbols-jagged-data-proessentials/main/docs/WpfChartBitmapSymbolsJaggedData.png" width="300" alt="wpf-chart-bitmap-symbols-jagged-data-proessentials"></a> | **Bitmap Symbols + Jagged Data**<br>[WPF](https://github.com/GigasoftInc/wpf-chart-bitmap-symbols-jagged-data-proessentials) · [WinForms](https://github.com/GigasoftInc/winforms-chart-bitmap-symbols-jagged-data-proessentials)<br><br>.NET 8 — a `Pesgo` scatter chart combining custom PNG bitmap symbols with jagged data (a different point count per subset). Direct2D. |

---

## Why ProEssentials vs the Competition?

➡️ [WPF Chart Library Comparison](https://gigasoft.com/why-proessentials)
➡️ [Performance — GPU Architecture Comparison](https://gigasoft.com/why-proessentials/performance)
➡️ [Licensing & Deployment Pain Comparison](https://gigasoft.com/why-proessentials/licensing-deployment)
➡️ [Plot 100 Million Points — 5-Library Comparison](https://gigasoft.com/blog/plot-100-million-points-wpf-comparison)
➡️ [3D Scientific Charts](https://gigasoft.com/why-proessentials/3d-scientific-charts)

---

📦 [NuGet](https://www.nuget.org/profiles/GigasoftInc) &nbsp;|&nbsp; 🌐 [gigasoft.com](https://gigasoft.com)



