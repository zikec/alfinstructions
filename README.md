# ATO Local File Instructions 2025 (Complied PDF) 

## Why I Built This

If you work in transfer pricing in Australia, you know the frustration of trying to save a copy of the ATO’s Local File Instructions offline.

The "Print whole topic" or "PDF whole topic" function is rarely helpful. You usually end up with a bloated file full of unclickable links, flattened images, and zero navigation. Trying to search for a specific rule or feed the document into an AI tool becomes a nightmare because the structure just isn't there.

I decided to fix this for myself, and I realised others in the tax community would find it useful too. 

## What This Is

This repository contains a structured, compiled PDF version of the 2025 Instructions, generated using a custom Python script I architected.

Instead of just taking screenshots of the webpages, this document:

- **Restructures Content:** Converts fragmented webpages into a single, cohesive book with searchable text and a working table of contents.

- **Fixes Navigation:** Internal cross-references work natively. You can jump between sections (e.g. from cover page to the appendices) without getting kicked back to your web browser. (Note: Blue links are internal; Red links will take you back to original ATO pages).

- **Cleans the Noise:** Automatically strips navigation bars, "Ask Alex" widgets, and web-only artifacts.

- **Optimises for AI:** Injects hierarchy so that if you use Retrieval-Augmented Generation (RAG) tools or LLMs, they can actually "read" and cite the document correctly.

## Licensing & Architecture Ownership

**License:** [Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/)

**Terms of Use**

- **You are free to:** Share, copy, and distribute this document in its entirety for any purpose, including commercial use.

- **You must:** Attribute the compilation architecture to the author (**Zike Chen**).

- **You may NOT:** Remix, transform, or build upon the material (e.g. stripping the metadata, removing the watermarks, or deleting the legal notice) and distribute the modified material.

**Project Origin & Capacity:**

This project was developed as a **personal initiative** outside of professional employment scope, hours, and infrastructure. The compilation architecture and automation logic are the independent intellectual contribution of the author (**Zike Chen**) and are not associated with any current or past employer.

## Non-Endorsement Disclaimer

The textual regulatory guidance contained herein is sourced from the Australian Taxation Office (ATO) and is subject to Commonwealth of Australia copyright. It is reproduced here in accordance with the standard ATO Copyright Notice.

This document is a third-party compilation and is NOT an official ATO document. The ATO and the Commonwealth do NOT endorse this specific file, its author, or any services associated with it.

## Liability Waiver

This document was generated using automated extraction tools. While every effort has been made to ensure fidelity to the source, the author has *not* manually verified every artifact. Therefore: 

- There is NO guarantee of error-free content.

- The author accepts NO liability for negative consequences, compliance failures, or financial loss resulting from the use of this document.

**Always verify critical technicalities against the official live ATO website.**

## Known Issues & Feedback

I am releasing this as Version 1.0 to get it into the hands of peers who need it.

- **Numbering:** You may notice some itemised lists (e.g. 1., 2., 3.) rendering with slight indentation quirks or numbering resets. I am actively refining the CSS logic to fix this in v1.1.

I welcome your feedback on structure and usability.

## Download & Access
You can download the compiled PDF directly from the [GitHub](https://github.com/zikec/alfinstructions) repository. 
1. Click on the `ATO_Local_File_Instructions_2025...pdf` file in the file list.
2. Click the **"Download raw file"** button (the small download icon near the top right of the file viewer) to save it to your computer.