# PDF_Extract_and_NER
Extract text from a PDF and perform Named Entity Recognition and visualize the entity tagging, People, Locations and Organizations

pip install pymupdf spacy
python -m spacy download en_core_web_sm

If you're running a heftier rig, the entity tagging will be more accurate with en_core_web_lg.

I've found en_core_wb_sm to be about 64-68% accurate while en_core_web_lg is closer to 74-78% accurate.

Script extracts text from a PDF using PyMuPDF (imported as fitz - inspired by F Scott Fitzgerald, an American novelist and essayist) 
and then applies Named Entity Recognition (a Natural Language Processing technique) via Spacy using the small english core web model
to identify people, places and organizations and lastly visualizes the tagging through DisplaCy.

We didn't start the fire lyrics because it's chock full of entities!
