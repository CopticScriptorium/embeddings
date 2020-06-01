# embeddings
Continuous word representations for Coptic

## Introduction

This repository contains work in progress for the development of word embeddings for Sahidic Coptic. The initial release contains proof of concept 50 dimensional embeddings trained with word2vec on approx. 1 million words with a vocabulary of about 10K items. The vocabulary assumes segmented forms based on Coptic Scriptorium guidelines (no bound-group embeddings are included).

## Data

The current embeddings are based on the entire available Sahidic text of the Old Testament (CoptOT project text), New Testament (Sahidica version) and all Coptic Scriptorium dev data as of Spring 2020. Data is mostly automatically segmented using CopticScriptorium/Coptic-NLP though gold segmentation was used for Scriptorium data where available.