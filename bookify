#We need install pdfkit package

import pdfkit

def url_to_pdf (url, pdf_path):
    try:
        pdfkit.from_url(url, pdf_path)
        print(f"PDF saved in {pdf_path}")
    except Exception as e:
        print(f"Oh noo..Error {e}")

url_input = 'https://en.wikipedia.org/wiki/Music'


pdf_path = '/home/g/Documents/music.pdf'


url_to_pdf(url_input, pdf_path)
