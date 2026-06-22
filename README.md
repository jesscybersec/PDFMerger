# PDF Merger

```diff
+ Merge PDFs locally
+ Reorder files with drag and drop
+ Make scanned documents searchable with OCR
- No cloud upload required
```

PDF Merger is a local-first Python and Streamlit application for organizing,
reordering, and merging PDF collections.

PDF Merger est une application Python et Streamlit qui permet d'organiser, de
réordonner et de fusionner localement des collections de PDF.

## Choose your language / Choisissez votre langue

### [🇬🇧 English documentation](PDFMerger-EN.md)

### [🇫🇷 Documentation française](PDFMerger-FR.md)

---

## Visual workflow / Parcours visuel

### 1. Select a source / Sélectionner une source

Choose between uploaded files and a local folder, then add the PDFs.

Choisissez le téléversement ou un dossier local, puis ajoutez les PDF.

![Select a PDF source and upload files](assets/screenshots/01-select-pdf-source.png)

### 2. Configure and merge / Configurer et fusionner

Add more PDFs, choose the output options, and start the merge.

Ajoutez d'autres PDF, configurez les options de sortie et lancez la fusion.

![Configure PDF Merger and start the merge](assets/screenshots/02-configure-and-merge.png)

### 3. Download / Télécharger

Download the completed PDF when processing finishes.

Téléchargez le PDF final lorsque le traitement est terminé.

![Download the completed merged PDF](assets/screenshots/03-download-result.png)

---

## Quick start / Démarrage rapide

### Kali Linux / Debian

```bash
git clone https://github.com/jesscybersec/PDFMerger.git
cd PDFMerger
chmod +x install_kali.sh
./install_kali.sh
```

### Run / Exécution

```bash
source venv/bin/activate
streamlit run PDFMerger.py
```

Streamlit should make the interface available at:

```text
http://localhost:8501
```

> [!IMPORTANT]
> PDF Merger is distributed as a standalone GitHub repository.

---

```text
╔═══════════════════════════════════════════════════════╗
║  LOCAL FILES IN // ONE SEARCHABLE PDF OUT           ║
║  CYBERJESS LAB // PRIVACY MODE ENGAGED              ║
╚═══════════════════════════════════════════════════════╝
```
