---
title: DYAD Audit Report
author: 0xnightswatch
date: September 29, 2025
geometry: a4paper, top=2cm, bottom=2cm, left=2cm, right=2cm
fontsize: 10pt
mainfont: TeX Gyre Termes
monofont: Inconsolata
linestretch: 1.1
header-includes:
  - \usepackage{graphicx}
  - \usepackage{listings}
  - \lstset{
    breaklines=true,
    breakatwhitespace=true,
    basicstyle=\ttfamily\tiny,
    keywordstyle=\color{blue},
    commentstyle=\color{gray},
    stringstyle=\color{teal},
    numbers=left,
    numberstyle=\tiny,
    stepnumber=1,
    numbersep=5pt,
    frame=single,
    rulecolor=\color{black!30},
    columns=fullflexible,
    keepspaces=true
    }
  - \usepackage{xurl}
  - \usepackage{hyperref}
  - \hypersetup{
    colorlinks=true,
    urlcolor=blue,
    linkcolor=blue,
    breaklinks=true
    }
  - \usepackage{titlesec}
  - \titleformat{\section}{\large\bfseries\color{blue}}{\thesection}{1em}{}
  - \titleformat{\subsection}{\normalsize\bfseries\color{teal}}{\thesubsection}{1em}{}
  - \titleformat{\subsubsection}{\small\bfseries\color{black!80}}{\thesubsubsection}{1em}{}
---

\begin{titlepage}
\begin{center}

\includegraphics[width=0.5\textwidth]{logo.pdf}

\vspace{2cm}

{\Huge\bfseries Dyad Audit Report\par}
\vspace{0.5cm}
{\Large Version 1.0\par}
\vspace{1cm}
{\Large\itshape 0xnightswatch\par}

\vfill

{\large \today\par}

\end{center}
\end{titlepage}

\newpage

<!-- Your report starts here! -->

Prepared by: [0xnightswatch](https://x.com/0xnightswatch)

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Protocol Summary](#protocol-summary)
- [Disclaimer](#disclaimer)
- [Risk Classification](#risk-classification)
- [Audit Details](#audit-details)
  - [Scope](#scope)
  - [Roles](#roles)
- [Executive Summary](#executive-summary)
  - [Issues found](#issues-found)
- [Findings](#findings)
  - [High](#high)
  - [Medium](#medium)
  - [Low](#low)
  - [Informational](#informational)
  - [Gas](#gas)

# Protocol Summary

Protocol does X, Y, Z

# Disclaimer

0xnightswatch makes all effort to find as many vulnerabilities in the code in the given time period, but holds no
responsibilities for the findings provided in this document. A security audit is not an endorsement of the underlying business
or product. The audit was time-boxed and the review of the code was solely on the security aspects of the Solidity
implementation of the contract.

# Risk Classification

|            |        | Impact |        |     |
| ---------- | ------ | ------ | ------ | --- |
|            |        | High   | Medium | Low |
|            | High   | H      | H/M    | M   |
| Likelihood | Medium | H/M    | M      | M/L |
|            | Low    | M      | M/L    | L   |

# Audit Details

**The findings in this document corresponds to the following commit hash:**

```
Commithash:
```

## Scope

## Roles

# Executive Summary

- Start Date:
- End Date:

## Issues found

| Severity       | Number of Issues |
| -------------- | ---------------- |
| High           |                  |
| Medium         |                  |
| Low            |                  |
| Informantional |                  |
| Gas            |                  |
| Total          |                  |

# Findings

## High

## Medium

## Low

## Informational

## Gas
