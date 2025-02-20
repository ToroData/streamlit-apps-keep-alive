# Streamlit Apps Keep Alive

This repository contains GitHub Actions workflows designed to periodically ping my Streamlit applications hosted on Streamlit Community Cloud. This prevents the applications from being put to sleep due to inactivity.

## Current Apps Monitored

- [Quantum Tech Papers](https://quantum-tech-papers.streamlit.app/)
- [Quantum Random Number Generator](https://quantum-random-number-generator.streamlit.app/)
- [Quantum Database Architecture EIT](https://quantum-database-architecture-eit.streamlit.app/)

## How It Works

A GitHub Action sends daily HTTP requests to the URLs of the Streamlit applications to keep them awake.

## Schedule

- Daily at 06:00 UTC

## Manual Execution

The workflow can also be triggered manually via the GitHub Actions tab.
