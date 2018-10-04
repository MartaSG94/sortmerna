# SortMeRNA User Manual

## Contents

# Introduction [[3]]
# Installation 3
## 2.1 Install from tarball release . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3
## 2.2 Install development version from git . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
## 2.3 Install from precompiled code . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  4
## 2.4 Uninstall . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  5
# 3 Databases 5
# 4 How to run SortMeRNA 5
## 4.1 Index the rRNA database: command `indexdb rna' . . . . . . . . . . . . . . . . . . 5
### 4.1.1 Example 1: indexdb rna using one database . . . . . . . . . . . . . . . . . . . 6
### 4.1.2 Example 2: indexdb rna using multiple databases . . . . . . . . . . . . . . . . 7
## 4.2 A guide to choosing ''sortmerna'' parameters for ltering and read mapping . . . . . 8
## 4.3 Filter rRNA reads . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
### 4.3.1 Example 3: multiple databases and the fastest alignment option . . . . . . . 11
### 4.3.2 Filtering paired-end reads . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
### 4.3.3 Example 4: forward-reverse paired-end reads (2 input les) . . . . . . . . . . 15
## 4.4 Read mapping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
### 4.4.1 Mapping reads for classication . . . . . . . . . . . . . . . . . . . . . . . . . . 17
### 4.4.2 Example 5: mapping reads against the 16S Greengenes 97% id database with multithreading  . . . 17
## 4.5 OTU-picking . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
# SortMeRNA advanced options 19
# Help 20
# Citation 20

== Introduction ==
SortMeRNA is a local sequence alignment tool for filtering, mapping and OTU-picking.
The core algorithm is based on approximate seeds and allows for fast and sensitive analyses
of NGS reads. The main application of SortMeRNA is filtering rRNA from metatranscriptomic data.
Additional applications include OTU-picking and taxonomy assignation available through [http://qiime.org QIIME v1.9+].
SortMeRNA takes as input a file of reads (fasta or fastq format) and one or multiple rRNA
database file(s), and sorts apart aligned and rejected reads into two files specified by the user.
SortMeRNA works with Illumina, 454, Ion Torrent and PacBio data, and can produce SAM and
BLAST-like alignments.

For questions help, please contact:

# xxx
# yyy
# zzz

This user manual is for SortMeRNA version 3

Sortmerna architecture and objects diagram

![smr diagram](https://github.com/biocore/sortmerna/blob/master/docs/sortmerna_1.svg "diagram")

== Databases ==

== Usage ==

== Getting Help ==

== Citation ==
∉
