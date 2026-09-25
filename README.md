# ANSI/ASME B73.1 process pump part item numbers, frame and group families, and size coverage

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22920668.svg)](https://doi.org/10.5281/zenodo.22920668)

A reference dataset published by **Jinan Yingsiman Machinery Co., Ltd. (YSM Pumps)**, Jinan, Shandong, China.

Version 1.0.0 · published 2026-09-23 · Licence: **CC BY 4.0** · DOI: [10.5281/zenodo.22920668](https://doi.org/10.5281/zenodo.22920668)

> **This is a mirror.** The citable record is on Zenodo: https://doi.org/10.5281/zenodo.22920668 (the concept DOI for all versions is
> https://doi.org/10.5281/zenodo.22920667). The five data files here are byte-identical to that deposit; their MD5 values are
> listed below and match the values Zenodo reports. Newer versions are released on Zenodo first.

## What this is

Item numbering on ANSI/ASME B73.1 horizontal end-suction process pumps is used constantly and written down in
machine-readable form almost nowhere. A maintenance planner reading a sectional drawing has to move between three
things: an item number, the part it identifies, and the frame or group that part belongs to. This dataset states that
mapping for one manufacturer's products so it can be cited, checked and corrected.

It covers two series:

- **G196 series**, built to the published Goulds 3196 dimensional pattern and organised by **frame** (STX, MTX, LTX, XLTX).
- **D Mark III series**, built to the published Durco Mark III dimensional pattern and organised by **group** (1, 2, 3).

## Files

| File | Rows | Contents | MD5 |
|---|---|---|---|
| `ysm-b73-item-numbers.csv` | 19 | Item/POS number, part, reference suffix, materials, what to confirm before ordering | 89b3521e3bb6ed13aa16ac211940cc12 |
| `ysm-b73-families.csv` | 6 | Frame and group families with the size designations each covers | 7acfc2d8a5ad9cc1796adcb072e1be1d |
| `ysm-b73-sectional-callouts.csv` | 104 | Which item numbers are called out on which sectional sheet | 3c5a74afd602bab167220e4be36f6d80 |
| `ysm-b73-size-reference.csv` | 60 | Size designations with casing and impeller references | fe87e3501aca0b6f649cfdbc473cbe90 |
| `ysm-b73-item-number-reference-v1.0.0.pdf` | 8 pp. | All four tables plus method, field definitions and limitations | 769d2912fb102905341a8aed447ce50d |

The tables below are rendered from the CSV files so they can be read without downloading anything.

## Table 1 - Item and POS numbers (19 rows)

Item number (G196) or POS number (D Mark III), the part it identifies, the manufacturer's reference suffix, the materials offered and what must be confirmed before ordering. Source file: `ysm-b73-item-numbers.csv`.

**G196 series, built to the published Goulds 3196 dimensional pattern (organised by frame)**

| Item / POS | Part | Ref. suffix | Materials offered | Confirm before ordering |
|---|---|---|---|---|
| 100 | Casing | 100 | WCB carbon steel, CF8M (316SS), CD4MCu duplex, CN7M (Alloy 20), Monel, Nickel, Hastelloy B and C, Titanium, Zirconium alloy | Size designation, flange rating and face, drain and gauge tappings |
| 101 | Impeller (open) | 3 | CF8M, CD4MCu, CN7M (Alloy 20), Monel, Nickel, Hastelloy B and C, Titanium, Zirconium alloy | Size, current trim diameter or duty point, impeller thread from the shaft |
| 184 | Stuffing box cover (packed box) | 106 | WCB, CF8M, CD4MCu, CN7M, Monel, Nickel, Hastelloy, Titanium | Frame and impeller diameter, gland bolting |
| 184M | Seal chamber (mechanical seal) | 106B, 106F | WCB, CF8M, CD4MCu, CN7M, Monel, Nickel, Hastelloy, Titanium | Standard bore, large bore or taper bore chamber; gland bolting; flush tappings |
| 108 | Frame adapter | 108 | Ductile iron | Frame and impeller diameter |
| 228 | Bearing frame | 119 | Cast iron; ductile iron for STX | Frame; oil-lubricated or oil-mist; sight glass and drain positions |
| 134 | Bearing housing | 201 | Per YSM drawing, stated at quotation | Frame; bearing arrangement fitted |
| 241 | Frame foot | 109 | Per YSM drawing, stated at quotation | Frame and impeller diameter |
| 122 | Shaft | 105, 105S | SAE 4140, 316SS, CN7M, Monel, Nickel, Hastelloy, Titanium | Whether a shaft sleeve is fitted (selects the 105 or 105S version); coupling-end diameter and keyway; impeller thread |
| 126 | Shaft sleeve | 177 | 316SS, CN7M, Monel, Nickel, Hastelloy, Titanium | Frame; seal setting dimension |

**D Mark III series, built to the published Durco Mark III dimensional pattern (organised by group)**

| Item / POS | Part | Ref. suffix | Materials offered | Confirm before ordering |
|---|---|---|---|---|
| 100 | Casing | 100 | WCB carbon steel, CF8M (316SS), CF3M (316L), CD4MCu duplex, super duplex, CN7M (Alloy 20), Monel, Nickel, Inconel, Hastelloy B and C, Titanium, Zirconium alloy | Size designation, flange rating and face, drain and gauge tappings |
| 103 | Reverse-vane impeller | 3 | CF8M, CF3M, CD4MCu, super duplex, CN7M, Monel, Nickel, Inconel, Hastelloy B and C, Titanium, Zirconium alloy | Size designation, current trim diameter or duty point, hub thread from the shaft |
| 106 | Rear cover plate | 106 (variants B, D, E) | WCB, CF8M, CF3M, CD4MCu, super duplex, CN7M, Monel, Nickel, Inconel, Hastelloy, Titanium | Group and impeller diameter; seal chamber type (CBS, CBL, FMS, FML or packed box); gland bolting |
| 108 | Bearing housing adapter | 108 | Ductile iron | Group and impeller diameter |
| 119 | Bearing housing | 119 | Ductile iron | Group; Mark 3 or Mark 3A; oil-lubricated or oil-mist |
| 201 | Bearing carrier | 201 | Per YSM drawing, stated at quotation | Group; bearing arrangement fitted |
| 109 | Bearing housing foot | 109 | Per YSM drawing, stated at quotation | Group and impeller diameter |
| 105 | Shaft | 105, 105S | SAE 4140, 316SS | Whether a hook sleeve is fitted (selects the 105 or 105S version); coupling-end diameter and keyway; impeller thread |
| 177 | Hook sleeve | 177 | Wet-end alloy of the pump | Group; seal setting dimension |

## Table 2 - Frame and group families (6 rows)

Which size designations each frame (G196) or group (D Mark III) covers. Source file: `ysm-b73-families.csv`.

| Series | Frame / group | Sizes covered |
|---|---|---|
| G196 | STX | 1x1.5-6, 1.5x3-6, 2x3-6, 1x1.5-8, 1.5x3-8 and the 1x1.5-8LF low-flow size |
| G196 | MTX / LTX | 8 in, 10 in and 13 in sizes from 2x3-8 to 4x6-13, including 3x4-8G, 3x4-10H, 4x6-10H and the LF low-flow sizes. MTX and LTX share casing, impeller and cover; the power-end parts differ. |
| G196 | XLTX | 6x8-13, 8x10-13, 6x8-15, 8x10-15, 8x10-15G |
| D Mark III | Group 1 | 1.5x1-6, 3x1.5-6, 3x2-6, 1.5x1-8, 3x1.5-8 and the 1.5x1LF-4 and 1.5x1LF-8 low-flow sizes |
| D Mark III | Group 2 | 8 in, 10 in and 13 in sizes from 3x2-8 to 6x4-13A, including the H and HH high-head hydraulics and the 2x1LF-10 and 3x1.5LF-13 low-flow sizes |
| D Mark III | Group 3 | 8x6-14A, 10x8-14, 6x4-16, 8x6-16, 8x6-16A, 10x8-16, 10x8-16H, 10x8-17 |

## Table 3 - Item numbers called out on each sectional sheet (104 rows)

Reported per sheet, because the sheets are not supersets of one another. Condensed here to one line per sheet; the CSV has one row per callout. Source file: `ysm-b73-sectional-callouts.csv`.

| Series | Sheet | Count | Item / POS numbers called out |
|---|---|---|---|
| G196 | STX sheet (sheet 1) | 19 | 100, 101, 112, 122, 126, 136, 168, 184M, 228, 250, 319, 332A, 333A, 351, 358A, 370, 418, 496, 496A |
| G196 | MTX sheet (sheet 2) | 22 | 100, 101, 108, 112, 122, 126, 136, 168, 184M, 228, 250, 319, 332A, 333A, 351, 358A, 360, 370, 418, 469B, 496, 496A |
| G196 | XLT-X sheet (sheet 3, XLTX frame) | 21 | 100, 101, 108, 112, 122, 126, 136, 168, 184M, 228, 250, 332A, 333A, 351, 358A, 360, 360A, 370, 418, 496, 496A |
| D Mark III | Exploded view (sheet 1) | 42 | 100, 103, 104, 105, 106, 107, 108, 109, 109A, 110, 111, 111A, 112, 113, 114, 115, 115A, 118, 119, 120, 121, 124, 125, 129, 130, 131, 133, 134, 135, 136, 139, 140, 153, 190, 190G, 200, 201, 201A, 201B, 201C, 201D, 201E |

## Table 4 - Size designations with casing and impeller references (60 rows)

Size designation (discharge x suction - nominal impeller diameter) with the manufacturer's casing and impeller references. Source file: `ysm-b73-size-reference.csv`.

**G196 series, built to the published Goulds 3196 dimensional pattern (organised by frame)**

| Size | Casing ref. | Impeller ref. |
|---|---|---|
| 1x1.5-6 | GAB100 | GAB3 |
| 1.5x3-6 | GAD100 | GAD3 |
| 2x3-6 | GKE100 | GKE3 |
| 1x1.5-8 | GAC100 | GAC3 |
| 1x1.5-8LF | GYB100 | GYB3 |
| 1.5x3-8 | GAE100 | GAE3 |
| 2x3-8 | GAF100 | GAF3 |
| 3x4-8 | GAG100 | GAG3 |
| 3x4-8G | GAGG100 | GAGG3 |
| 1x2-10 | GAH100 | GAH3 |
| 1x2-10LF | GYC100 | GYC3 |
| 1.5x3-10 | GAJ100 | GAJ3 |
| 2x3-10 | GAL100 | GAL3 |
| 3x4-10 | GAN100 | GAN3 |
| 3x4-10H | GAP100 | GAP3 |
| 4x6-10 | GAQ100 | GAQ3 |
| 4x6-10H | GAR100 | GAR3 |
| 1.5x3-13 | GAS100 | GAS3 |
| 1.5x3-13LF | GYD100 | GYD3 |
| 2x3-13 | GAT100 | GAT3 |
| 3x4-13 | GAU100 | GAU3 |
| 4x6-13 | GAW100 | GAW3 |
| 6x8-13 | GNA100 | GNA3 |
| 8x10-13 | GNB100 | GNB3 |
| 6x8-15 | GNF100 | GNF3 |
| 8x10-15 | GNC100 | GNC3 |
| 8x10-15G | GND100 | GND3 |

**D Mark III series, built to the published Durco Mark III dimensional pattern (organised by group)**

| Size | Casing ref. | Impeller ref. |
|---|---|---|
| 1K1.5x1LF-4 | DYA100 | DYA3 |
| 1K1.5x1-6 | DKA100 | DKA3 |
| 1K3x1.5-6 | DKC100 | DKC3 |
| 1K3x2-6 | DKE100 | DKE3 |
| 1K1.5x1LF-8 | DYB100 | DYB3 |
| 1K1.5x1-8 | DKB100 | DKB3 |
| 1K3x1.5-8 | DKD100 | DKD3 |
| 2K3x2-8 | DAF100 | DAF3 |
| 2K4x3-8 | DAG100 | DAG3 |
| 2K2x1LF-10 | DYC100 | DYC3 |
| 2K2x1-10A | DAH100 | DAH3 |
| 3x1.5-10 | DAJ100 | DAJ3 |
| 2K3x1.5-10A | DAK100 | DAK3 |
| 3x2-10 | DAL100 | DAL3 |
| 2K3x2-10A | DAM100 | DAM3 |
| 2K4x3-10 | DAN100 | DAN3 |
| 2K4x3-10H | DAP100 | DAP3 |
| 2K6x4-10 | DAQ100 | DAQ3 |
| 2K6x4-10H | DAR100 | DAR3 |
| 2K3x1.5LF-13 | DYD100 | DYD3 |
| 2K3x1.5-13 | DAS100 | DAS3 |
| 2K3x2-13 | DAT100 | DAT3 |
| 2K4x3-13 | DAU100 | DAU3 |
| 2K4x3-13HH | DAV100 | DAV3 |
| 2K6x4-13A | DAW100 | DAW3 |
| 3K8x6-14A | DNA100 | DNA3 |
| 3K10x8-14 | DNB100 | DNB3 |
| 3K6x4-16 | DNE100 | DNE3 |
| 8x6-16 | DNF100 | DNF3 |
| 3K8x6-16A | DNG100 | DNG3 |
| 3K10x8-16 | DNC100 | DNC3 |
| 3K10x8-16H | DND100 | DND3 |
| 3K10x8-17 | DNH100 | DNH3 |

## Method

Every value in Tables 1, 2 and 4 was extracted **programmatically** from tables already published on the
manufacturer's own website on 2026-09-22, not transcribed from drawings or scanned documents. The extraction reads the
published HTML tables and normalises the size-designation separator to `x`. Because the dataset is generated from those
pages rather than retyped, it cannot silently drift from them.

The **sectional callout table (Table 3) is the exception**: those item numbers were read off the manufacturer's own
sectional drawings by a person, sheet by sheet. They are reported per sheet rather than merged, because the sheets are
not supersets of one another: item 319 appears on the STX and MTX sheets but not on XLT-X, and 360A only on XLT-X. The
drawing labels that frame **XLT-X** while the manufacturer's prose calls it **XLTX**; the sheet labels here follow the
drawing.

## Field definitions

| Field | Meaning |
|---|---|
| `series` | `G196` or `D Mark III`, the manufacturer's own series name |
| `pattern` | The published dimensional pattern the series is built to |
| `item_no` | Item number (G196) or POS number (D Mark III) used for that part on a sectional drawing |
| `part` | What the item number identifies |
| `ysm_ref_suffix` | The manufacturer's own reference suffix for that part |
| `materials` | Material options offered for that part |
| `confirmed_before_order` | What must be confirmed from the nameplate or drawing before that part is ordered |
| `family` | The frame (STX, MTX, LTX, XLTX) or group (1, 2, 3) a set of sizes belongs to |
| `sizes` | Size designations that family covers, as discharge x suction - nominal impeller diameter |
| `sheet` | Which sectional sheet a callout appears on |
| `pump_size` | A size designation |
| `casing_ysm_ref`, `impeller_ysm_ref` | The manufacturer's references for the casing and impeller of that size |

## Limitations and scope

- **No OEM part numbers are included.** Item numbers here are the standard item and POS numbering used on B73.1
  sectional drawings; the reference suffixes are this manufacturer's own.
- Goulds, 3196, Durco and Mark III are trademarks of their respective owners. They are named only to identify the
  published dimensional pattern a series is built to. YSM Pumps is an independent manufacturer, **not affiliated with,
  sponsored by or endorsed by ITT Goulds Pumps or Flowserve**.
- Interchange applies to a pump of the same size designation **and frame or group**, confirmed against the nameplate
  and the installed pump drawing. Nothing in this dataset states that a part will fit a specific installed pump.
- Values are catalogue ranges for screening and identification, not guarantees for every size and configuration. A
  quotation is confirmed against size-specific reviewed documents.
- This dataset describes one manufacturer's products. It is not a survey of the industry and should not be read as one.

## Sources

These tables were compiled from the publisher's own published pages:

- Goulds 3196 pattern parts, with materials: https://ysmpumps.com/goulds-3196-pump-parts/
- Durco Mark 3 pattern parts, with materials: https://ysmpumps.com/durco-mark-3-pump-parts/
- Replacement pumps and parts programme: https://ysmpumps.com/replacement-ansi-pump-parts/
- Summit 2196 replacement, size coverage: https://ysmpumps.com/product/summit-2196-replacement/
- How a B73.1 size designation is built: https://ysmpumps.com/resources/ansi-pump-size-codes/

## How to cite

> Jinan Yingsiman Machinery Co., Ltd. (YSM Pumps). (2026). *ANSI/ASME B73.1 process pump part item numbers, frame and group families, and size coverage: a reference dataset* (Version 1.0.0) [Dataset]. Zenodo.
> https://doi.org/10.5281/zenodo.22920668

```bibtex
@dataset{ysm_pumps_2026_22920668,
  author    = {{Jinan Yingsiman Machinery Co., Ltd. (YSM Pumps)}},
  title     = {ANSI/ASME B73.1 process pump part item numbers, frame and group families, and size coverage: a reference dataset},
  year      = {2026},
  publisher = {Zenodo},
  version   = {1.0.0},
  doi       = {10.5281/zenodo.22920668},
  url       = {https://doi.org/10.5281/zenodo.22920668}
}
```

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0). You may share and adapt the data for any purpose, provided
you give appropriate credit, link to the licence and indicate if changes were made.

## Corrections

Errors can be reported to the publisher. Corrections are issued as a **new version of the Zenodo record** rather than by
editing published files, and this mirror is then updated to match. Any newer version supersedes this one.

## About the publisher

Jinan Yingsiman Machinery Co., Ltd., trading as YSM Pumps, manufactures ANSI/ASME B73.1 chemical process pumps and
non-OEM replacement pumps and wet-end parts built to the same dimensional patterns, plus ISO 5199/2858, API 610 OH2,
multistage, vertical turbine and paper stock pumps. The company was registered in Jinan in 2018; its works in Zibo,
Shandong has been in operation since 2010.

https://ysmpumps.com
