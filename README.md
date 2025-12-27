# Professor-Review-Rating-Predictor-with-RoBERTa
Pulls a bunch of reviews for UMD CS professors from PlanetTerp and fine-tunes roberta-base to classify them.

Uses the PlanetTerp API (python wrapper) to pull reviews from a list of professors.
https://planetterp.com/api/

The reviews all have a corresponding rating which the roberta model is trained to predict.


