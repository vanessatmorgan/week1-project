# Week-1 Project Summary

This repository contains the most up to date version of the code for our week 1 project

We decided to use the average cortical thickness from all regions in the “aparc.DKTatlas” as our predictor features, dropping non-numeric and high-missing regions, and excluding subjects at the minimum p-factor to reduce skew. We then compressed the features with PCA and compared SVR, Random-Forest, and linear regressors via repeated k-fold validation. The best pipeline (Random Forest) is retrained on the full cleaned data and used to predict the test set p-factor scores.

# Group Members:

Annika Andersson

Deepa Prasad

Denisse Bolaños-Ramirez

Florencia Altschuler

Juan Pablo Garcia

Kathy Zhang

Kush Thakkar

Lord Boateng Amponsah

Tien Tong

Vanessa Morgan

Yosef Schwartz