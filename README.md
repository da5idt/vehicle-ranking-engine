# Vehicle Ranking Engine

The Vehicle Ranking Engine is a Databricks-based solution designed to help users make data-driven vehicle comparisons by integrating data from NHTSA and additional sources. The system ingests, stores, and evaluates vehicle data based on user-defined priorities to generate transparent, rank-ordered vehicle recommendations.

## Solution Overview

- 🚗 **Data Ingestion**  
  Automatically pulls vehicle data from NHTSA and other relevant public sources.

- 💾 **Data Storage**  
  Lands all collected data into a Delta Lakehouse within Databricks for scalable, reliable storage and analytics.

- 📊 **Evaluation Engine**  
  Applies a flexible, weighted scoring model based on user-specified preferences for various vehicle features.

- 🏆 **Ranked Results**  
  Produces a ranked list of vehicles including:
    - Overall score for each vehicle
    - Detailed scoring breakdown for each feature

## Purpose

This solution enables users to evaluate and compare vehicles using consistent, transparent data tailored to their needs. The goal is to simplify vehicle research by providing ranked, data-backed insights to support smarter decision-making.

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this project for both personal and commercial purposes, provided that the original copyright and license notice are retained.
