# Multiple Sequence Alignment of Bovine MMP Genes

## Project Overview
Multiple sequence alignment of three bovine matrix metalloproteinases (MMP1, MMP8, MMP13) using Clustal Omega to identify and analyze the conserved Zn²⁺ binding site.

## Sequences Analyzed
- **MMP13_BOVIN** (O77656) - Collagenase 3
- **MMP1_BOVIN** (P28053) - Interstitial collagenase  
- **MMP8_BOVIN** (XP_024831456.2) - Neutrophil collagenase

## Key Findings
- **Successful alignment** of all three MMP sequences using Clustal Omega
- **Identified conserved Zn²⁺ binding site**: `HEXXHXXGXXH` motif
- **Histidine residues** at positions 201, 205, 211 (MMP13) coordinate zinc ion
- **High conservation** in catalytic domain across all bovine MMPs

## Methodology
1. **Sequence retrieval** from NCBI
2. **Multiple sequence alignment** using Clustal Omega
3. **Visual analysis** of conserved regions
4. **Identification** of Zn²⁺ binding site motif

## Repository Contents
- `data/MMPS.fasta` - Input sequences in FASTA format
- `data/alignment.clustal` - Clustal Omega alignment output
- `images/clustal_alignment.png` - Visualization of alignment
- `images/zn_binding_site.png` - Highlighted zinc binding site

## Zinc Binding Site Results
| Gene  | Position | Motif         | Conservation |
|-------|----------|---------------|-------------|
| MMP13 | 201-211  | HEFGHSLGLDH   | 100%        |
| MMP1  | 197-207  | HEFGHSLGLAH   | 100%        |
| MMP8  | 202-212  | HEFGHSLGLAH   | 100%        |

![Alignment Results](images/clustal_alignment.png)
*Clustal Omega multiple sequence alignment results*

![Zinc Binding Site](images/zn_binding_site.png)  
*Conserved Zn²⁺ binding site motif highlighted in alignment*
