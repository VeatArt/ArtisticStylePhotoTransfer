# ArtisticStylePhotoTransfer
Simple Artistic Style Transfer

FirstTryBackError ist die erste Implementation mit Problemen in der Bildberechnung

Simplere Alternative ist eingesetzt: LoopedArtisticStyleTransfer.
Vortrainiertes Modell wird als tfhub-Modul eingesetzt, basierend auf: Golnaz Ghiasi, Honglak Lee, Manjunath Kudlur, Vincent Dumoulin, Jonathon Shlens. Exploring the structure of a real-time, arbitrary neural artistic stylization network, 2017.

Umgesetzt in Colab mit Python(-cuda) und tensorflow. Daten werden hier über definierten Ordner in Google Drive aufgegriffen (content_images, content_image_path, style_image) und gespeichert (file_path, file_name) Weitere Optionen zum (image-)target_size und style_strength vorhanden.
