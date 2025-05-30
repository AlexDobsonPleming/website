---
layout: post
title: "COM4521 GPU Assignment: Results Aggregator Tool"
date: 2025-05-30
tags: [com4521, cuda, openmp, parallel-computing, visual-studio]
---

I built this tool in just two days as part of the 2024/2025 **COM4521 Parallel Computing with GPUs** assignment at the University of Sheffield. It’s a lightweight GUI app designed to make it much easier to run, compare, and benchmark the various solutions (CPU, OpenMP, and CUDA) for the assignment tasks.

---

## ⚙️ What it does

The Results Aggregator helps you:

- Run your assignment programs with different configurations
- Compare runtimes across implementations (CPU vs OpenMP vs CUDA)
- Benchmark performance across increasing difficulty levels
- Export data quickly to Excel for making submission graphs
- Generate different resolutions of images for Chromatic Aberration

It's GUI-based and built in Visual Studio using .NET, with a simple copy–paste workflow into Excel for graphing.

---

## 📥 Download

[➡️ Latest release on GitHub](https://github.com/AlexDobsonPleming/ParallelRunner/releases/latest)

> ⚠️ **Note**: You may see a Smartscreen warning—this is just because I haven’t paid for EV code signing.  
> 💡 If you're using University Managed Desktops, you're better off cloning the repository and running it in Visual Studio instead of downloading the `.exe`.

---

## 📈 Graphing in Excel

You can copy the table output directly into Excel to generate performance graphs.  
Just avoid copying the "Length" column, as Excel may treat it as another data series.

![how to make graphs](/assets/parallel_runner/charting.png)

---

## 📸 Screenshots

**Product of Differences**

![Product of Differences](/assets/parallel_runner/product%20of%20differences.png)

**Chromatic Aberration**

![Chromatic Aberration](/assets/parallel_runner/ca.png)

---

