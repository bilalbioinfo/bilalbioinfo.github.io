---
layout: page
permalink: /repositories/
title: repositories
description: Open-source software and pipelines I develop and maintain.
nav: true
nav_order: 3
---

<style>
  .repo-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
  }
  .repo-card {
    display: flex;
    flex-direction: column;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-radius: 0.6rem;
    padding: 1rem 1.1rem;
    background-color: var(--global-card-bg-color, transparent);
    transition: transform 0.15s ease, box-shadow 0.15s ease, border-color 0.15s ease;
    text-decoration: none !important;
  }
  .repo-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.12);
    border-color: var(--global-theme-color);
  }
  .repo-card .repo-name {
    font-weight: 700;
    color: var(--global-theme-color);
    font-size: 1.02rem;
    margin-bottom: 0.35rem;
    word-break: break-word;
  }
  .repo-card .repo-name i { margin-right: 0.4rem; }
  .repo-card .repo-desc {
    color: var(--global-text-color);
    font-size: 0.85rem;
    line-height: 1.4;
    flex-grow: 1;
    margin-bottom: 0.7rem;
  }
  .repo-card .repo-lang {
    font-size: 0.72rem;
    color: var(--global-text-color-light, #828282);
    display: inline-flex;
    align-items: center;
  }
  .repo-card .repo-lang::before {
    content: "";
    display: inline-block;
    width: 0.65rem;
    height: 0.65rem;
    border-radius: 50%;
    background: var(--global-theme-color);
    margin-right: 0.4rem;
  }
</style>

<div class="repo-grid">

  <a class="repo-card" href="https://github.com/NBISweden/DNAharvester">
    <div class="repo-name"><i class="fa-brands fa-github"></i>NBISweden/DNAharvester</div>
    <div class="repo-desc">A Nextflow pipeline for analysing highly degraded DNA from ancient and historical specimens — competitive/adaptive mapping, reference-bias evaluation, and subworkflows for mitogenome assembly, taxonomy, sex determination, and variant calling.</div>
    <span class="repo-lang">Nextflow</span>
  </a>

  <a class="repo-card" href="https://github.com/bilalbioinfo/SNP2NET">
    <div class="repo-name"><i class="fa-brands fa-github"></i>SNP2NET</div>
    <div class="repo-desc">Creates an interactive circular phylogenetic network from SNP data using Neighbor-Joining.</div>
    <span class="repo-lang">Python</span>
  </a>

  <a class="repo-card" href="https://github.com/bilalbioinfo/iterative_mapping">
    <div class="repo-name"><i class="fa-brands fa-github"></i>iterative_mapping</div>
    <div class="repo-desc">Nextflow pipeline for iterative mapping of nuclear genomes.</div>
    <span class="repo-lang">Nextflow</span>
  </a>

  <a class="repo-card" href="https://github.com/bilalbioinfo/dna-capture-probes-design">
    <div class="repo-name"><i class="fa-brands fa-github"></i>dna-capture-probes-design</div>
    <div class="repo-desc">Scripts to design hybridization probes to capture genome-wide nuclear SNPs, missense mutations, and indels.</div>
    <span class="repo-lang">Python</span>
  </a>

  <a class="repo-card" href="https://github.com/bilalbioinfo/AdaptClean">
    <div class="repo-name"><i class="fa-brands fa-github"></i>AdaptClean</div>
    <div class="repo-desc">Removes residual adapter sequences for single-end reads.</div>
    <span class="repo-lang">C++</span>
  </a>

</div>
