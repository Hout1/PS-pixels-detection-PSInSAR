#PS pixels detection PSInSAR
Neural Network-based approach for identification of PS pixels in PSInSAR.
Persistent Scatterer Interferometric Synthetic Aperture Radar (PSInSAR)
is a remote sensing method, which uses isolated radar scatterers that
maintain high coherence for long periods such as
boulders, tree trunks, and buildings.
To identify such pixels from contaminated interferograms, we investigate a variety of deep learning approaches:
CNN-based approach to capture the spatial nature of noise in interferograms and directly map the contaminated phases to its Phase consistency.
ANN-based approach considering only the temporal variations in amplitude and phase angles of pixels.
CNN-based auto-encoders to denoise the interferograms, followed by an LSTM based architecture to map these cleaned interferograms to their Phase consistencies.