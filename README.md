# Color-Rebirth

Color-Rebirth è un progetto che trasforma video in bianco e nero in video a colori. Grazie a tecniche di deep learning e al modello pre-addestrato DeOldify, il progetto colora automaticamente i fotogrammi. Inoltre, integra un color picker che permette agli utenti di specificare quali colori mantenere.

## Caratteristiche Principali

- **Colorizzazione Automatica dei Video:**  
  - Il progetto sfrutta il modello DeOldify per trasformare video in bianco e nero in capolavori a colori.

- **Color Picker:**  
  - Integra il riconoscimento per elaborare comandi e preservare specifici colori sugli oggetti desiderati.

- **Segmentazione degli Oggetti:**  
  - Utilizza tecniche di segmentazione per isolare gli oggetti in base alle indicazioni dell'utente.

- **Interfaccia Utente Intuitiva:**  
  - Offre una GUI semplice e funzionale (basata su Electron con Node.js per interfacciarsi tramite Drive e per elaborare il progetto in Colab) che facilita l'elaborazione e la personalizzazione del video.

## Tecnologie Utilizzate

- Python con OpenCV per l'elaborazione dei video
- PyTorch (con supporto CUDA) per l'esecuzione dei modelli di deep learning
- DeOldify per la colorizzazione dei video
- Electron per l'interfaccia grafica
