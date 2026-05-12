# Bioinformatics Term Project

## Overview
RNA-seq, RPF (Ribosome Profiling), CLIP-seq 데이터를 활용한 유전자 발현 및 번역 조절 분석 프로젝트

## Main Analysis
- **Mission 1**: 데이터 전처리 및 기본적인 발현 분석
  - RNA-seq, RPF, CLIP-seq 데이터의 카운트 및 필터링
  - Scatter plot을 통한 발현 분석 (논문 Figure 4D 유사)
  - Protein localization 반영한 분석 (논문 Figure 5B, S6A 유사)
- **Mission 2**: Start Codon 주변의 RPF (Ribosome-Protected Fragment) 분포 분석
  - Start codon 주변 5'-end 분포 확인
  - 3nt 주기성(periodicity) 관찰
  - Transcript Support Level (TSL) 1 및 Positive strand 기준 필터링
- **Mission 3**: CLIP-seq 분석
  - 각 position별 base 수 계산
  - Shannon entropy 계산 및 bedgraph format 출력
  - UCSC Genome Browser를 통한 시각화 (Mirlet7d, Mirlet7f-1 등)

## Visualization
- Scatter plot (발현 분석)
- Protein localization analysis (색상으로 localization 반영)
- RPF distribution around start codon (3nt 주기성)
- CLIP-seq entropy bedgraph (UCSC Genome Browser)

---
Jeonghyun Lee <hsikt16@gmail.com>
