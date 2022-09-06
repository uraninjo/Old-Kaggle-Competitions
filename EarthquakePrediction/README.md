# LANL Earthquake Prediction

The goal of this competition is to use seismic signals to predict the timing of laboratory earthquakes. The data comes from a well-known experimental set-up used to study earthquake physics. The acoustic_data input signal is used to predict the time remaining before the next laboratory earthquake (time_to_failure).

The training data is a single, continuous segment of experimental data. The test data consists of a folder containing many small segments. The data within each test file is continuous, but the test files do not represent a continuous segment of the experiment; thus, the predictions cannot be assumed to follow the same regular pattern seen in the training file.

For each seg_id in the test folder, you should predict a single time_to_failure corresponding to the time between the last row of the segment and the next laboratory earthquake.

## https://www.kaggle.com/competitions/LANL-Earthquake-Prediction/overview

Yarışma için skor, hesaplanan özelliklerin arttırılması ve train.csv'den okunan verilerin arttırılmasıyla artacaktır fakat benim bilgisayarım arttırdığımda hata veriyor. Şimdilik fikir ve verinin nasıl işleneceği, anlamak için yeterlidir.
